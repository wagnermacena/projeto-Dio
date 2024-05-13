mkdir MeuProjeto
cd MeuProjeto
echo "# MeuProjeto" >> README.md
git init
git add README.md
git commit -m "Adicionar README"
git branch -M main
git remote add origin https://github.com/seu_usuario/MeuProjeto.git
git push -u origin main
