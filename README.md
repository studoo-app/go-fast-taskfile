![separe](https://github.com/studoo-app/.github/blob/main/profile/studoo-banner-logo.png) 
# GO FAST TASKFILE
![CI](https://github.com/bfoujols/setup-symfony-projet/actions/workflows/testing.yml/badge.svg)

Pour limiter la répétition des commandes, voici une proposition d'un makefile orienté crossPlatform TaskFile. \
Plus d'information : [https://taskfile.dev/](https://taskfile.dev/)

### 1. Prérequis

Gestionnaire de package :

- [ ] Pour Windows -> Installer Scoop : [https://scoop.sh/](https://scoop.sh/)
- [ ] Pour MacOs -> Installer Brew : [https://brew.sh/](https://brew.sh/)

Stack à installer :
- [ ] Installer TaskFile > v3.20 : [https://taskfile.dev/installation/](https://taskfile.dev/installation/)
- [ ] Installer Docker : [https://docs.docker.com/get-docker/](https://docs.docker.com/get-docker/)
- [ ] Installer Docker Compose : [https://docs.docker.com/compose/install/](https://docs.docker.com/compose/install/)
- [ ] Installer PHP : [https://www.php.net/manual/fr/install.php](https://www.php.net/manual/fr/install.php)
- [ ] Installer Composer : [https://getcomposer.org/download/](https://getcomposer.org/download/)
- [ ] Installer Symfony CLI : [https://symfony.com/download](https://symfony.com/download)

Optionnel :
- [ ] Installer NodeJS : [https://nodejs.org/en/download/](https://nodejs.org/en/download/)

### 2. Installation Taskfile dans le projet

```bash
curl -fsS https://raw.githubusercontent.com/bfoujols/setup-symfony-projet/main/Taskfile.yaml > Taskfile.yaml
```

### 3. Initialisation du projet 

```bash
task start
```