# Capgemini - Desafio Backend | Java

Olá! Esse desafio técnico tem como propósito medir suas habilidades, ver como estuda, pensa e se organiza na prática, o  framework é de sua escolha mas a linguagem é java

Após finalizar o desafio, de preferencia faça um fork do projeto depois pull request, nos envie um link para repositório do projeto ou um zip com o código o que se sentir mais confortavel.

Existem diversas maneiras distintas de solucionar o problema que estamos propondo. Vamos listar algumas sub-tasks que podem guiá-lo(a) em relação a essas possibilidades.

## O desafio
Usuários Bradesco realizam diversos pagamentos pix por todo o Brasil, o desafio é fazer uma API em Java que persista os pagamentos pix e listar os pagamentos pix. No response de pagamentos, deve informar a porcentagem referente ao valor do pagamento feito pelo usuario na data dd/mm/yyyy representa  dos valores dos pagamentos totais do mês vigente.
Construir um micro-service que por sua vez terá um endPoint "/pagamentos"devolverá para o usuário final um payload em JSON contendo os  dados para pagamento.

## Input
Você deve criar um micro-service que conterá um path e um endPoint que receberá  dados em formato JSON contendo algumas informações de dados de pagamento PIX.


## Output
Você deve criar um micro-service que conterá um path e um endPoint que enviara  dados em formato JSON contendo a lista de pagamentos PIX e cada pagamento com sua porcentagem.


### Dados a serem coletados do pagamento pix :

* Nome destinatario
* CPF
* Instituição Bancaria
* Chave pix
* Valor
* Descrição
* Porcentagem do pagamento  (Ex: aplicar uma regra de porcentagem com base no valor do pagamento pix em relação ao mês que ele foi realizado )

## Alguns pontos cruciais para entrega

* Criação de uma API que seja capaz de receber requesições feitas utilizando json e persistindo esses dados.
* Porcentagem do pagamento PIX

## Alguns pontos que serão bonús:

* Utilizar o frameowork Jarx-rs, spring boot ou struts
* Organização do código 
* Organização do repositorio remoto
* Fork e Pull request
* CRUD completo de pagamentos pix.
* Testes Unitarios (TDD)
* Código bem comentado 
* Facilidade ao rodar o projeto
* Utilização de padrões de projeto 
* Utilização de DDD

## Dúvidas do processo, avisar que finalizou a prova, enviar link do projeto remoto ou enviar zip do projeto

Enviar e-mail para  lucas.reis@capgemini.com , kamila.castelano@capgemini.com , vinicius.pascucci@capgemini.com ou  levi.ferreira@capgemini.com.


**Happy coding! :-)**
