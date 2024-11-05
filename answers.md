# Answers of <students-firstname> <students-lastname> <github-username>

## Basics
### Task 1
- answers.md
- img folder
    - gitgraph.svg
- .git folder
    - Multiple files and folders 
    Ces fichiers et dossiers sont cachés de base. Ceux-ci sont utilisés pour stocker les informations de git.

### Task 2
Avec le 'git status' on observe que le fichier "README.md" n'est pas suivi
Le 'git log --oneline' reste inchangé

### Task 3
Le 'git status' nous indique que le nouveau fichier "README.md" est suivi et que le answers.md est modifié
Le 'git log --oneline' reste inchangé

### Task 4
Le 'git status' nous indique que le fichier "answers.md" et README.md sont modifiés
Le 'git log --oneline' reste inchangé

### Task 5
Le numéro au début de chaque ligne du 'git log --oneline' est l'identifiant du commit
HEAD et main nous signifie sur quelle branche nous sommes
Entre parenthèse c'est le nom de la branche sur laquelle le commit a été fait

### Task 6
Lors du checkout avec le premier commit, tous le smodification du fichier "answers.md" ont été supprimé et le fichier "README.md" a été supprimé. Lors du checkout avec le main, les modifications du fichier "answers.md" ont été rétabli et le fichier "README.md" a été rétabli.

## Gitgraph

### Task 7
1. Nom de la branche
2. Identifiant du commit
3. Message du commit
4. Utilisateur qui a fait le commit (nom et email)
5. Version du commit
6. Commit avec merge du feature-auth sur develop
7. Commit/branch du feature-auth
8. Commit avec merge du develop sur main et creation du branch feature-auth à partir du main
9. Branch develop
10. Branch main

![Gitgraph](img/gitgraph.svg)