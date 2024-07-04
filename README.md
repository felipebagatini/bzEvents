1 - Na primeira aba, a login, existe uma validação para logar, tem que usar o usuario Felipe e senha felipe08 para passar
2 - A tela de chat deixei em branco pois é algo dinamico, e como é só layout criei a tela pra ter a base
3 - A aba de mapa funcionou na primeira vez e a partir da segunda vez começou a fechar o app, nao entendi muito bem pq, mas a aba existe, no futuro vai ser alterado
4 - Foi usado o fragment na aba cadastro de usuario, logo na primeira aba

Versão Final
1 - O login continua o mesmo, apenas alguns ajustes de perfomance e no campo de senha
2 - O mapa novamente não funcionou, então decidi remover a funcionalidade do mapa nessa versão
3 - Ao adicionar um evento, utilizando o conceito do SQLITE, deixei a data fixa, pois nos 5 primeiros testes consegui utilizar com o componente, porém depois parou de funcionar, então deixei o dia 5 ao adicionar na tabela do banco
4 - Agora da pra adicionar os eventos, ao adicionar os eventos ja carrega dinamicamente na listview da mainactivity e guarda na tabela "EVENTOS" que criei no arquivo "Banco.java"
