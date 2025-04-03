# 🖥️ **Minishell** - Projet École 42

<p align="center">
  <img src="https://github.com/mbah24-dev/mbah24-dev/blob/main/42_badges/pipexe.png" alt="Pipex 42 project badge"/>
</p>

Bienvenue dans **Minishell**, un projet inspiré du shell Unix, développé dans le cadre de la formation à l'école 42. L'objectif principal de ce projet est de créer un shell minimaliste en C, capable de gérer des commandes, des redirections, des pipes et plus encore.

---

## 📌 **Objectifs du projet**

- Créer un shell minimaliste mais fonctionnel.
- Implémenter les bases de gestion des commandes, des arguments et des erreurs.
- Gérer les redirections (`>`, `<`, `>>`, `<<`).
- Implémenter des pipes (`|`) pour rediriger les sorties d'une commande vers une autre.
- Supporter les commandes internes comme `cd`, `echo`, `exit`.
- Gérer les signaux et les processus enfants.

---

## 🚀 **Fonctionnalités**

- **Gestion des commandes** : Le shell doit être capable de recevoir et exécuter des commandes simples.
- **Redirections de fichiers** : Support des redirections `>`, `<`, `>>`, `<<`.
- **Pipes** : Le shell doit supporter les pipes (`|`) pour relier plusieurs commandes.
- **Commandes internes** :
  - `cd` : Changer le répertoire courant.
  - `echo` : Afficher des messages.
  - `exit` : Quitter le shell.
- **Gestion des erreurs** : Détection et gestion des erreurs de commande et de redirection.
- **Signaux** : Gérer les signaux pour contrôler les processus enfants.

---

## 🛠️ **Installation**

### Prérequis

- Compiler avec `gcc` (version 9 ou supérieure recommandée).
- Système Linux ou MacOS (compatible avec les fonctionnalités de `fork` et `exec`).
- Avoir un environnement compatible avec `libc`.

### Pour compiler et exécuter le projet :

```bash
git clone https://github.com/ton-utilisateur/minishell.git
cd minishell
make
./minishell
