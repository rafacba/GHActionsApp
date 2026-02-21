Para subir un proyecto a un repo de github existente:

git remote add origin https://github.com/tu-usuario/tu-repo.git
git add .
git commit -m "first commit"
git branch -M main
git push -u origin main

Si el repo ya tiene contenido, se debe hacer un pull antes de subir:

git pull origin main --allow-unrelated-histories

Para subir un proyecto a un repo de github nuevo:

git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/tu-usuario/tu-repo.git
git push -u origin main
