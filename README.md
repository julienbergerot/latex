# polytechnique-LaTeX
Code du package LaTeX de l'École polytechnique.

Pour l'installation de LaTeX et du package, se reporter au fichier `guide/installation.pdf`.

Il est aussi simple d'installer le package sous linux depuis le dépôt avec le `Makefile`, après l'avoir téléchargé (avec `git clone` ou en téléchargeant un `.zip` ou `.tar.gz`) :

```bash
cd polytechnique
make && make install
```

## Test

Vous pouvez essayer le code sur l'exemple du guide :

```bash
cd guide/
pdflatex installation.tex
```

## Pour Overleaf

Telecharger le dossier et extraire les fichiers.

Dans Overleaf, uploader les fichiers suivants:

```
source/polytechnique-armes.pdf
source/polytechnique-filetcourt.pdf
source/polytechnique-filetlongrouge.pdf
source/polytechnique-logohori.pdf
source/polytechnique-logovert.pdf
source/polytechnique.sty
```

Puis ajouter `\usepackage{polytechnique}` en haut de votre fichier `main.tex`.
