# Backend em NodeJS

## Conceitos:

### Rota
  Conjunto

### Recurso
  Recurso = usuário

### Métodos HTTP
  - GET: Buscar uma informação => e.g.: lista, item
  - POST: Criando uma informação
  - PUT: Editando uma informação
  - DELETE: Deletando uma informação

### Parâmetros
  - Query Params: http://localhost:3333/users?search=lucas
  - Route Params: http://localhost:3333/1 (identificar um recurso);
  - Body: http://localhost:3333/users

### Banco de dados
  - Driver nativo: Como estamos acostumados através de linha de comando.
  - Query builder: Knex, por exemplo => construtor de queries de banco de dados
  - ORM: maior nível de abstração possível; cada objeto é uma instância de entidade do banco.