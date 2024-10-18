# ``📚formulario de endeço completo``

## Descrição

>Este projeto consiste em um formulário de cadastro que valida informações essenciais, como e-mail, CPF e CEP. Ele também 
busca automaticamente os dados de endereço a partir do CEP informado, utilizando a API ViaCEP.

## Funcionalidades

 **1 Validação de E-mail**:

* Verifica se o e-mail informado contém um formato válido (deve incluir "@" e um domínio com ".").
Alerta o usuário se o e-mail for inválido.

**2 Validação de CPF**:

* Verifica se o CPF informado possui 11 dígitos e não é uma sequência de números repetidos.
Realiza a validação do CPF utilizando o algoritmo de cálculo de dígitos verificadores.

**3 Validação de CEP**:


* Aceita formatos de CEP com ou sem o hífen (ex.: 12345-678 ou 12345678).
Verifica se o CEP possui 8 dígitos.

**4 Busca de Endereço pelo CEP**:

* Ao perder o foco (blur) no campo de CEP, busca automaticamente os dados de endereço na API ViaCEP.
Preenche os campos de endereço (logradouro, bairro, cidade, UF) com as informações retornadas.

**5 Envio do Formulário**:

* Impede o envio do formulário caso alguma validação falhe.
Exibe uma mensagem de sucesso ao enviar o formulário corretamente.

## Como Usar

**Preencha o formulário**:

* Insira um e-mail válido.
* Insira um CPF válido.
* Insira um CEP e veja os dados do endereço serem preenchidos automaticamente.

**Envie o formulário**:

* Clique no botão de envio e verifique se todas as validações passaram.

## tecnologia Utilizada 
- HTML
- CSS
- JAVISCRIPT
- BOOTSTRAP
## links de projeto que usei de auxilio
- [validacao_Email_CPF](https://github.com/matheussantos1206/validacao_Email_CPF)
- [form-loginV2](https://github.com/matheussantos1206/form-loginV2)
- [Form-CadEndereco-](https://github.com/matheussantos1206/Form-CadEndereco-)

# RESULTADO 

![resultado](img/formulario%20login%20completo.png)

# autor:

[MATHEUS ROCHA DOS SANTOS](https://github.com/matheussantos1206)