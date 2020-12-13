# tf-poo-20201


IDE utilizada: IntelliJ IDEA 2020.2.3 (Ultimate Edition)

Banco de Dados utilizado: SQL Server - SQL Server Management Studio 15.0.18358.0

Bibliotecas externas: 
* mssql-jdbc-8.2.2.jre8 (Conexão com o Banco de Dados)
* JUnit

Tutorial de instação do sistema:

1 - Criação e configuração do Banco de Dados
* Faça o download do SQL Server + SQL Server Management Studio (MSSMS), para configuração do banco de dados.
* No MSSMS, entre com suas credenciais do Windows
* clique com o botão direito no servidor
* Propriedades
* Nas Propriedades do Servidor, clique em Segurança.
* Em Autenticação do servidor, selecione "Modo de Autenticação do SQL Server e do Windows" e em OK.
<hr>
* Expanda o servidor, expanda "Segurança", expanda "Logons", e selecione "sa"
* Em "Geral", mude a senha para admin, conforme estabelecido neste projeto.
* Clique me Status, na lista esquerda das propriedades do Logon - sa
* Torne o Logon Habilitado, e clique em OK.
<hr>
* Para criar as tabelas, utilize o script SQL, dentro da pasta docs, deste projeto.
<hr>
* Para rodas o sistema, é necessário habilitar as portas TCP-IP.
* Para isso, abra "SQL Server 2019 Configuration Manager", instalado junto com o MSSMS.
* Expanda "Configuração de Rede do SQL Server", e clique em "Protocolos para MSSQLSERVER.
* Habilite TCP/IP
* Abra TCP/IP e clique em "Endereços IP"
* Torne todas as portas IP ativas, e digite a porta 1433 em todas as portas TCP.
* Clique em Aplicar e OK.
