"" Mini-Compilateur – Projet de Compilation (FLEX & BISON) ""

*****Description du projet
Ce projet a pour objectif de développer un mini-compilateur capable de réaliser les principales phases du processus de compilation, depuis l’analyse lexicale jusqu’à la génération de code intermédiaire.
Le compilateur repose sur deux outils majeurs :
- FLEX pour l’analyse lexicale
-BISON pour l’analyse syntaxique et sémantique

L’objectif est de définir un petit langage de programmation personnalisé, puis d’en implémenter les différentes étapes de traitement : reconnaissance des tokens, vérification syntaxico-sémantique, gestion de la table des symboles, traitement des erreurs et génération du code intermédiaire sous forme de quadruplets.

*****Fonctionnalités principales

🔤 Analyse lexicale (FLEX) : définition des entités lexicales (identificateurs, mots-clés, opérateurs, constantes, etc.) à l’aide d’expressions régulières.
🧠 Analyse syntaxique et sémantique (BISON) : implémentation d’une grammaire LALR(1) du langage, avec gestion des priorités et associativités des opérateurs.
📚 Table des symboles : création et mise à jour dynamique des identifiants (variables, constantes, tableaux) au fil de la compilation.
⚠️ Gestion des erreurs : détection et affichage précis des erreurs lexicales, syntaxiques et sémantiques avec leur position dans le fichier source.
🧾 Génération du code intermédiaire : transformation du programme source en une représentation intermédiaire à base de quadruplets.

*****Structure minimale du langage

Le langage défini pour ce projet inclut :
La structure générale d’un programme
Les commentaires
La déclaration de variables simples et structurées
Les types de données personnalisés
Les instructions de base : affectation, condition, boucle, entrée/sortie
Les opérateurs arithmétiques, logiques et de comparaison
Les règles de priorité et d’associativité
