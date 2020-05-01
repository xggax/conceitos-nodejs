## Essa aplicação é do desafio 02 do Bootcamp GoStack da Rocketseat.

Essa será uma aplicação para armazenar repositórios do meu portfólio, que irá permitir a criação, listagem, atualização e remoção dos repositórios, e além disso permitir que os repositórios possam receber "likes".

Existem as rotas de POST, GET, PUT, DELETE dos repositórios, uma rota de POST para incrementar os likes dos repositórios, já que like seria uma entidade e repository seria outra.

Existem alguns testes incrementados para a validação da rota que foram escritos utilizando jtest. Para rodá-los basta yarn test.

### Esse projeto de conceitos do Nodejs utliza algumas bibliotecas:

- **[cors](https://github.com/expressjs/cors)
- **[uuidv4](https://www.npmjs.com/package/uuidv4)
- **[express](https://expressjs.com/pt-br/)
- **[jest](https://jestjs.io/)
- **[nodemon](https://nodemon.io/)
- **[supertest](https://github.com/visionmedia/supertest)

### Comandos:
- `yarn dev`: levantar o servidor.
- `yarn test`: testar a aplicação.

Algumas ferramentas de API Rest Client podem ser usadas para mandar requisições simulando o fluxo para as rotas com dados, como por exemplo o [insomnia](https://insomnia.rest/).