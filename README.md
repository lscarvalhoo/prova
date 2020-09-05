# prova
Prova Desenvolvimento UCDB

Para visualizar e executar o projeto recomento(Ultizadas no desenvolvimento da aplicação) as seguintes ferramentas
Pacote Entity Framework
Pacote Entity Framework Tools
Visual Studio 2019


Descompacte o arquivo prova.zip, dentro da pasta Prova, execute o arquivo "Prova.sln"
Com o projeto aberto, selecione o Terminal de gerenciamento de pacotes Nugget localizado em
Ferramentas -> Gerenciador de Pacotes do Nugget -> Console do Gerenciador de pacotes
Em seguida execute o seguinte comando
Install-Package Microsoft.EntityFrameworkCore.SqlServer
Logo após,
Install-Package Microsoft.EntityFrameworkCore.Tools
Na pasta Models dentro da solução exite a classe de contexto do banco de dados
certifique-se de colocar a string que de conexão da sua máquina no meu caso
(localdb)\mssqllocaldb.
Em seguida ainda no console do gerenciador digite o comando
Add-Migration (escolha o nome do migration)
e por fim o comando
Update-Databe 

A aplicação já estara "pronta para funcionar"
