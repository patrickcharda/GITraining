Git est un dvcs : distributed version system control

Git gère les modifs apportées aux fichiers selon 3 états :
- modifié -> le fic a été modifié mais modifs non ajoutées à la bdd locale
- indexé -> la version du fichier a été ajoutée au prochain lot de modifs qui seront intégrées à la bdd locale
- validé -> la version du fichier est présente ds la bdd locale

=> .git directory (repository) -> checkout the project 
=> working directory -> stage fixes
=> staging area -> commit

> git --version

> git config --global user.name "John Doe"
> git config --global user.mail "patrick.chardavoine@gmail.com"

> git config --global --list -> affiche config globale de git telle que précédemment définie

> git config --global autocorrect 1 -> permet à git de proposer des solutions aux erreurs de saisie de cmde par exemple

> mkdir testbox
> cd textbox
> git init
> echo -e "#fichier README.md\n\n Ne contient pas grand chose" > README.md
> git add README.md
> git commit -m "first commit"




