### Documentação dos comandos utilizados no terminal Linux para prática de gerenciamento de permissões,grupos, usuários e proprietários

- sudo useradd [usuário] - Comando utilizado para criar novos usuários
  
- sudo groupadd [grupos] - Comando utilizado para criar novos grupos
  
- sudo usermod -aG [grupo] [usuarios] - Comando utilizado para adicionar um usuario ao grupo
  
- getent group [grupo] - Como utilizado para verificar usuários de um grupo
  
- touch [arquivo] - Comando utilizado para criar um novo arquivo
  
- setfacl -m g:[grupo]:[permissões] [arquivo] - Comando utilizado para definir as permissões especificas para um grupo com ACL
  
- getfacl [arquivo] - Como utilizado para consultar as permissões ACL de um arquivo
  
- sudo chown [usuario] [arquivo] - Comando utilizado para alterar o proprietario de um arquivo
  
- ls -l [arquivo] - Comando utilizado para visualizar o proprietario, grupo e permissões de um arquivo
  
- sudo chmod [permissões] [nome do arquivo] - Comando utilizado para alterar as permissões de um arquivo
  
- sudo chmod 700 [arquivo] - Comando utilizado para definir as permissões do proprietario, grupo e outros usuarios
