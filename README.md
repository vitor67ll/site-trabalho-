# site-trabalho-
hotel eveitto
# GUIA COMPLETO: PUBLICAÇÃO DO SITE NO GITHUB PAGES

# PARTE 1: PRÉ-REQUISITOS (Execute apenas uma vez para um novo projeto)
# Inicializar o repositório Git local (se for a primeira vez)
# git init

# Associar o repositório local ao repositório remoto (exemplo)
# Substitua <URL_DO_SEU_REPO> pelo URL do seu repositório no GitHub
# git remote add origin <URL_DO_SEU_REPO>

# PARTE 2: COMANDOS ESSENCIAIS PARA SUBIR O FICHEIRO (AS TRÊS LINHAS MÁGICAS)

# 1. Certifique-se de que está na pasta do seu repositório
#    (Pode usar 'ls' para verificar se o 'index.html' está lá)

# 2. Adicione o novo ficheiro (prepara o 'index.html' para ser enviado)
git add index.html

# 3. Confirme as alterações (cria um ponto de salvamento na história)
git commit -m "Deploy: Thailand Summit final website"

# 4. Envie o ficheiro para o GitHub (transfere a versão local para o servidor remoto)
git push origin main 

