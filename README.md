# Novo Ambiente no Azure

![alt text](https://github.com/leandroscardua/azure_environment/blob/master/Drawing2.jpg)

Com este powershell script vamos criar uma novo ambiente no Azure, com este script vamos criar um ambiente conforme exemplicado na imagem, segue e lista com todos os itens que serao criados:

- Resource Group
- Virtual Network
- Network Security Group (NSG)
- Storage Account
- Availability Set Group
- Load Balance com servidor participantes do Availabily Set Group
- Uma VM com uma controlador de Dominio
- Uma VM com servico de RDS instalado
- Uma ou mais VM(s) para rodar Servicos Web ( IIS ou similar )
- Uma ou mais VM(s) para rodar Aplicacoes como servicos no windows
- Uma ou mais VM(s) para rodar Aplicacoes em Linux ( Redis ou similiar )
- Uma ou mais VM(s) para rodar Microsoft SQL Server
- Uma ou mais VM(s) para rodar Microsoft SQL Server com Availabily Set Group

Obs: Para a alteracao das configuracoes, faca as mudancas necessarias no script antes de executar o script.







