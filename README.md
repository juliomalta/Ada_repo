# Normalização de Tabelas, seguinto a 1ª, 2ª e 3ª Forma Normal (FN)

A normalização de dados é um conceito base no design de bancos de dados relacionais. Trata de uma forma normativa
de organização dos dados de forma que reduza a redundância e potencialize a integridade dos dados, facilitando a manutenção
e a escalabilidade do sistema.

Através de exemplos concretos, demonstraremos como transformar uma tabela desorganizada em estruturas normalizadas que atendem
a esses critérios.

## Primeira Forma Normal (1FN).
  
![forma1](https://github.com/juliomalta/Ada_repo/blob/main/T1.png)

Todos os atributos de uma tabela devem ser atômicos e monovalorados.
### Após Normalização: 
![forma1.1](https://github.com/juliomalta/Ada_repo/blob/main/T1.1.png)
![forma1.2](https://github.com/juliomalta/Ada_repo/blob/main/T1.2.png)

## Segunda Forma Normal (2FN).
![forma2](https://github.com/juliomalta/Ada_repo/blob/main/T2.png)

É preciso estar na 1FN

Todos os atributos não chaves da tabela devem depender unicamente da chave
primária

Dependências parciais não são permitidas
### Após Normalização: 
![forma2.1](https://github.com/juliomalta/Ada_repo/blob/main/T2.1.png)
![forma2.2](https://github.com/juliomalta/Ada_repo/blob/main/T2.1.png)

## Terceira Forma Normal (3FN).
![forma3](https://github.com/juliomalta/Ada_repo/blob/main/T3.png)

É preciso estar na 2FN

Os atributos não chave de uma tabela devem ser mutuamente independentes e
dependentes unicamente e exclusivamente da chave primária
### Após Normalização: 
![forma3.1](https://github.com/juliomalta/Ada_repo/blob/main/T3.1.png)
