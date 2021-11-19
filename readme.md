# Desafio 01 - Conceitos do Node.js (DADOS EM MEMORIA)
NodeJs

### Routes 

* POST /users
* GET / todos
* POST /todos
* PUT /todos/:id
* PATCH /todos/:id/done
* DELETE /todos/:id

### rules de negócio

* Criar um novo todo;
* Listar todos os todos;
* Alterar o title e deadline de um todo existente;
* Marcar um todo como feito;
* Marcar um todo como feito;

### Dependencies

* Expression 
* Nodemon
* Uuid

### Retorno Metodo post users
```sh
{ 
	id: 'uuid', // precisa ser um uuid
	name: 'Samuel', 
	username: 'Samuel Nunes', 
	todos: []
}
```

### Retorno Metodo post todos
```sh
{ 
	id: 'uuid', // precisa ser um uuid
	title: 'Nome da tarefa',
	done: false, 
	deadline: '2021-02-27T00:00:00.000Z', 
	created_at: '2021-02-22T00:00:00.000Z'
}
```
