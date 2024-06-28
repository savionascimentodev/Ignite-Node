# Fundamentos do Node.js

### Rotas

As rotas são caminhos de entrada da api, quando, são meios de entrada e formas como o nosso cliente (front-end) executar diferentes operações dentro do nosso back-end, por exemplo:

- Rotas para criar usuários;
- Rotas para demover usuários;
- Rotas para editar usuários...

#### Requisição Http

Uma requisição HTTP é composta por dois principais recursos:

- **Método Http:**
  - O método HTTP especifica a ação que o cliente deseja que o servidor realize. Os métodos mais comuns são:
    - **GET:** Recupera dados do servidor.
    - **POST:** Envia dados para o servidor.
    - **PUT:** Atualiza dados no servidor.
    - **DELETE:** Remove dados do servidor.
    - **PATCH:** Atualiza parcialmente os dados no servidor.
    - **OPTIONS:** Descreve as opções de comunicação para o recurso de destino.
- **URL:**
  - A URL identifica o recurso no servidor com o qual o cliente deseja interagir. Ela é composta por vários componentes, incluindo:
