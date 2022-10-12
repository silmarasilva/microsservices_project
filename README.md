<h1><b> Microsserviço <b></h1>

Projeto para cadastro de doações de roupa - moda circular -para pessoas em situação de rua.


# Tecnologias Utilizadas

1. Python 3.8
2. MySQL 
3. Postman
4. Visual Studio Code


# Bibliotecas Python


# Passo a passo 

# DEPLOY: 

1. Rodar a aplicação: 
cd app:

Windows: 

- py clientes.py

Linus: 

- python3 clientes.py


2. Acessar os dados via Browser ou Postman - lembrando que o banco precisa estar instalado e os dados precisam ter sido criados na máquina local.
- http://localhost:5100/clientes
- http://localhost:5200/enderecos
- http://localhost:5300/produtos
- http://localhost:5400/servicos


# Observações:

- API CLIENTES
- No método PUT, passar o número do id no body. Pegar o número via GET
- No caso de delete, passar o número do id na url. Ex.: http://localhost:5100/clientes/25

- API ENDERECOS:
- Para fazer um POST o idEndreço e o IdCliente deve ser passdo no body/raw da API manualmente

- API PRODUTOS
- A api de produtos possui um funcionalidade interessante que é a possibilidade de se alterar o id do curso no body passando o id atual do curso na url.

- API VENDAS
- Como a api de vendas chama as apis de clientes e produtos, para que ela funcione corretamente é necessário rodar as demais API's em outro(s) terminais.

# Para listar as dependências

pip install -r requirements.pip
pip freeze ou pip list


# Bibliotecas 

Windows - pip install 
Ubuntu - sudo apt install 
