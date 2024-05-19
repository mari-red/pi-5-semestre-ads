## PROVA DE CONCEITO

Inicialmente, o projeto trata de um serviço cujo objetivo principal é 
facilitar o acesso a treinamentos personalizados, informações sobre saúde e 
nutrição, servindo como um acompanhamento adequado para a prática de 
exercícios físicos.  

Dentre as funções previstas para o aplicativo, definimos como prova de 
conceito para ser desenvolvida a jornada do usuário e o registro do tempo 
de um treino realizado.

Foram desenvolvidas as segintes telas:

- Cadastro (usuários que entram pela primeira vez no serviço)

O cadastro deve ser efetivado com a entrada dos dados referentes ao nome,
e-mail e uma senha pessoal do usuário.


- Início (página inicial)
  
O login deve ser efetuado somente através do e-mail e senha cadastrados
pelo usuário.


- Telas para registrar a jornada do usuário;

As informações foram centralizadas numa única tela, onde são apresentados 
os dados cadastrados na jornada, bem como possibilita o acesso às 
funcionalidades de registrar o tempo de um treino e emitir um 
relatório PDF com os registros dos treinos.



- Telas para acessar e registrar o tempo do treino realizado

Nessa tela, o usuário poderá selecionar a modalidade esportiva que 
pretende executar, ativar um cronômetro quando iniciar o exercício e 
pausá-lo quando finalizar. Além disso, para iniciar uma nova contagem 
de tempo, poderá resetar o cronômetro.



## REVISITANDO O PROJETO

Para o Projeto Integrador V, foi configurado o banco de dados (inexistente na primeira prova
de conceito). Foi escolhida a ferramenta do Supabase, sendo utilizada tanto para a autenticação dos
usuários (houve mudança do Firebase para o Supabase) quanto para o banco de dados.

O banco de dados possui 4 tabelas, que incluem os registros dos usuários, características dos usuários,
os tipos de exercícios, e os registros dos exercícios realizados pelo usuário.   

Além disso, foi inserida a função de gerar relatório dos registros de exercícios.
Ao revisitar o projeto original, identificamos necessidade de algumas 
alterações nas telas relacionadas à prova de conceito, de forma que 
pudessem ser adequadamente desenvolvidas:


### Link do protótipo no Figma:
https://www.figma.com/design/oM62i81gcvRUpgisfNRUFC/PI?node-id=0-1&t=L4KOKOSvqnEKW6Ne-0


### Grupo 22:
- João Lucas Mota Marques Dias
- Marina Lobato Ramos Vermelho
- Thalia Carneiro de Araujo
- Carolina Kazumi Nakamura
- Frederico Azzarini Neutzling
- Gabriel dos Santos Silva
- Gabriel Evaristo Vieira
- Juvenal Silveira da Silva Neto

