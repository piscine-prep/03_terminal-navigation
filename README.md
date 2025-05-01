# Exercice 3 : Navigation dans le terminal

## Objectif

Apprendre à naviguer dans votre système de fichiers en utilisant les commandes de base du terminal. Cet exercice vous enseignera comment visualiser, créer et vous déplacer entre les dossiers - compétences essentielles avant de commencer à coder.

## Commandes à Apprendre

- `pwd` - Afficher le dossier de Travail (Print Working Directory)
- `ls` - Lister le contenu du dossier
- `cd` - Changer de dossier (Change Directory)
- `mkdir` - Créer un dossier (Make Directory)

## Exercice

### Partie 1: Exploration

1. Ouvrez votre terminal
2. Déterminez votre emplacement actuel en utilisant la commande appropriée
3. Listez tous les fichiers et dossiers à votre emplacement actuel
4. Listez tous les fichiers et dossiers, y compris les fichiers cachés
5. Naviguez vers votre dossier personnel
6. Créez une structure de dossiers comme suit:
   ```
   ~/c_piscine/
   └── shell/
       ├── ex00/
       ├── ex01/
       └── ex02/
   ```
7. Naviguez à travers cette structure en utilisant des chemins relatifs et absolus

### Partie 2: Documentation

Créez un fichier texte appelé `navigation_log.txt` à l'intérieur du dossier `ex00` qui contient:

1. La commande pour afficher votre dossier actuel
2. La commande pour lister tous les fichiers, y compris les fichiers cachés, avec des informations détaillées
3. La commande pour naviguer vers le dossier parent
4. La commande pour naviguer vers votre dossier personnel quel que soit l'emplacement actuel

## Résultat Attendu

Lorsque nous exécutons `cat ~/c_piscine/shell/ex00/navigation_log.txt`, nous devrions voir les commandes correctes pour chaque tâche.

## Conseils

- Souvenez-vous que `~` est un raccourci pour votre dossier personnel
- Utilisez `man [commande]` pour en savoir plus sur chaque commande
- Essayez d'utiliser la complétion par tabulation pour gagner du temps lors de la saisie des chemins
