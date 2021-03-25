# api-challenge
MVP desenvolvido em .net core 3.1
-Descompactar arquivo da pasta zip, e abrir o arquivo de extensão .sln.
-Executar a aplicação, e utilizá-la pelo swagger no browser.

Métodos:
POST -> api/cliente:
Enviar o seguinte objeto {
	"clientes":[

		{
		   "id":"1",
		   "nome":"Maria Sousa",
		   "cpf":"258.851.854-74",
		   "salario":"2500.77"		
		},
		{
		   "id":"2",
		   "nome":"Jose Santos",
		   "cpf":"358.800.700-01",
		   "salario":"1851.88"		

		
		},
		{
		   "id":"3",
		   "nome":"Miguel Castro Silva",
		   "cpf":"269.855.888-51",
		   "salario":"3854.21"
		
		},
		{
		   "id":"4",
		   "nome":"Amanda Gasper Libero",
		   "cpf":"258.587.854-55",
		   "salario":"8755.00"
		
		},
		{
		   "id":"5",
		   "nome":"Thais Alcantara Machado",
		   "cpf":"211.855.854-99",
		   "salario":"1250.01"
		
		}

	]

}

GET -> /api/Cliente/GetById
-Informar o id no método no swagger

GET - > /api/Cliente/GetByCpf
-Informar o cpf no método no swagger
