# Instruções 
Para execução do código é necessário subir um servidor local com o resultado da API. 
1) abrir a pasta "backend" no cdm
2) executar os comandos 
   - ```npm init –y```
   - ```npm install --save -dev json-server```
3) ao finalizar a instalação adicionar a seguinte informação no arquivo "package.json" que foi criado automaticamente na pasta “backend”

```
"scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "server1": "json-server --watch user.json --port 3001"
  },
  ```
  
  
# Atividades
Os alunos deverão desempenhar as seguintes atividades:
1. Na carga inicial da aplicação, obter os dados de:
https://randomuser.me/api/?seed=javascript&results=100&nat=BR&noinfo
2. Carregar os dados dos usuários em um array.
3. Permitir a filtragem de usuários através de um input com interação do usuário.
4. O usuário poderá filtrar dados quando digitar pelo menos um caractere no input.
5. O usuário poderá filtrar os dados tanto digitando "Enter" quanto clicando no botão
correspondente, conforme imagens mais abaixo.
6. Montar dois painéis.
7. No painel da esquerda, listar os usuários filtrados.
8. No painel da direita, calcular e mostrar algumas estatísticas sobre esses usuários,
conforme imagens abaixo.
