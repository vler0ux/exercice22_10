création d'un dossier dans dev
git.init
git.status -> branch main
on copie colle la commande dans le git.init

```bash
git config --global init.defaultBranch <name>
```
il faut supprimer la branche main
```bash
rm -r .git
git status
git init
git status
```

on met à jour dans local :

```bash
git add. 
git commit -m "premier commit"
```