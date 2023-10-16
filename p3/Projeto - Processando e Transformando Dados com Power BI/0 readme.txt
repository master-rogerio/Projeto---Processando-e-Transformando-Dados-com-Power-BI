1 - Foi criado uma conta gratuita no azure;

2 - Criado Banco de dados utilizando a base de dados presente no GitHub
	2.1 - O código apresentado no Github continha erros, impossibilitando a inserção do mesmo diretamente o Bash do Azure. Assim foi realizado correção do mesmo para que os dados fossem inseridos adequadamente.
3 - Foi realizado a conexão entre PowerBI e Azure, realizando a integração dos sistemas

4 - Foi verificado se havia problemas na base de dados.

5 - Foi verificado se os tipos de dados estavam corretos em cada coluna, e corrigido eventuais erros de atribuição.

6 - Foi realizado a junção do Funcionário com seu respectivo supervisor na tabela Employee.

7 - Foi realizado a Mescla entre employee e department (Chamada de Company works_on).

8 - Remoção das colunas desnecessárias.

9 - Realizado a Mescla entre Nome e Sobrenome dos funcionários.

10 - Realizado o nomes de departamentos e sua localização.

11 - Agrupado em nova tabela (Employees por Supervisor) a quantidade de funcionários por gerente.

12 - Tanto Mesclar quanto Acrescentar são utilizados para juntar duas ou mais tabelas diferentes. A diferença entre eles é que:
 - Mesclar realiza a junção combinando as duas tabelas, utilizando como base alguma coluna em comum (com os mesmos dados) de ambas as tabelas;
 - Enquanto Acrescentar combina ambas as tabelas somando as linhas e colunas das tabelas acrescentando toda as informações na tabela que foi selecionada como origem.

Por isso no caso o item 13, do desafio de projeto, é necessário utilizar Mesclar. Para que seja combinado os departamentos com a localização de forma que os dados continuem relacionados.
