# Estudo de Banco de Dados

Neste repositório contém conceitos básicos e introdutórios sobre banco de dados, sendo recomendável como meio de consultas rápidas. Para informações mais aprofundadas, é recomendado que você realize pesquisa mais aprofundadas ou leia obras consagradas da área.

## Conceitos e definições


### Banco de dados

É um sistema capaz de armazenar grandes quantidades de dados de forma estruturada e organizada, possibilitando rápido acesso e manuseio.

### Banco de dados relacionais

São banco de dados que utilizam mecanismos baseados em chaves de identificação para relacionar os elementos, estes elementos são estruturados em forma de tabelas.

### Tabela

As tabelas são as abstrações utilizadas pelo banco para mapear os elementos do mundo real, em uma tabela de banco de dados, cada **coluna** representa uma característica (ex. código, nome, email, sexo), e cada linha representa uma ocorrência, também chamado de **registro** (ex. 001, José Raimundo, jose@email.com, Masculino), exemplo:

| codigo | nome | email | sexo |
|--|--|--|--|
| 001 | José Raimundo | jose@email.com | Masculino |
| 002 | Gabriela Alves | galves@email.com	| Feminino |
| 003 | Felipe Pedrosa | fepedrosa@email.com | Masculino |


### Abstração

Ao trabalhar com banco de dados, é fundamentação uma boa capacidade de abstração, uma vez que devemos limitar e ajustar nosso cenário virtual com o cenário real do nosso problema, por exemplo, ao desenvolver um banco que armazena dados de compradores, informações como nome, CPF, data de nascimento, são importantes para o funcionamento da aplicação, porém dados como cor dos olhos, altura, peso, etc. são dispensáveis, e apenas causariam volume desnecessário em nosso banco de dados.

### Atomicidade

Consiste em quebrar o máximo possível a informação para o armazenamento. Por exemplo, se consideramos um endereço, temos um campo contendo uma imensa variável: [Rua 25 de Março, N 188, São Paulo-SP]. Ao aplicar o conceito de atomicidade, cada elemento do endereço será tratado como uma parte, preenchendo seu respectivo campo, Exemplo: [Rua 25 de Março], [188], [São Paulo], [SP]. Com essa abordagem, é possível informações mais especificas e mais rápido do banco quando se trata de análises considerando conjuntos maiores, Exemplo: Endereços de uma rua ou estado especifico.





### Relacionamentos







### Banco de dados

## Data Manipulation Language (DML)

Os comandos DML possibilitam a manipulação dos dados armazenados no banco de dados.


### Insert



### Update



### Delete



### Select


