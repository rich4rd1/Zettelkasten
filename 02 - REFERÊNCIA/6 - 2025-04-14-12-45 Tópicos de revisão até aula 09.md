---
ID: 6 - 2025-04-14-12-45
tags:
  - nota-referência
Tema: "[[6 - SISTEMAS DE BANCOS DE DADOS]]"
---
---
# REFERÊNCIA
https://aprender3.unb.br/pluginfile.php/3113420/mod_resource/content/1/Aula06_Generalizacao.pdf
sobre generalização para revisar se precisar.


---
# RELEVÂNCIA
---
# NOTAS RELACIONADAS
---
# RESUMO

#### CONJUNTO DE ENTIDADES

**ENTIDADE**: Coisa, pessoas, objetos etc.
**CONJUNTO DE ENTIDADES**: coleção de entidades que tem o mesmo significado
 **NOTAÇÃO**: retângulos.
**CHAVE:** Deve ter um atributo, ou conjunto de atributos que garantam sua unicidade (chave), onde a chave identifica univocamente cada entidade. Se uma entidade necessita mais de um atributo para ser identificado todos esses atributos podem ser concatenados e defini-los como uma **chave única**
#### CONJUNTO DE RELACIONAMETOS

**ASSOCIAÇÃO**: entre entidades do mundo real
**CONJUNTO** DE RELACIONAMENTOS: relacionamento entre entidade do mesmo CEs.
 **NOTAÇÃO**: losango.

#### ATRIBUTOS DE ENTIDADES

**ATRIBUTOS**: Valores que representam propriedades das entidades
 **NOTAÇÃO:** elipses ligada aos conjuntos de entidade


#### ATRIBUTOS DE RELACIONAMENTO

**NÃO** precisam necessariamente de atributos, pode acontecer de que alguns atributos podem dar mais sentido ou evitar maiores problemas futuros se forem atribuídos ao relacionamento. 

#### ATRIBUTOS

 Podem ser simples ou compostos. Sendo que os simples não podem ser divididos. Pegue endereço como exemplo, como atributo simples ele apenas seria uma string que poderia se colocado o endereço por completo lá, ele sendo composto podemos dividi-lo em rua, numero, cep, cidade.

 Atributos podem ser **monovalorados** ou **multivalorados**, onde o monovalorado indica que é apenas um atributo de uma entidade ou relacionamento particular. O multivalorado pode ser assumir mais de um valor para uma entidade ou relacionamento.  

 Temos atributos armazenados e derivados, onde os armazenados são da entidade e os derivados podem vir de outras entidades ou relacionamentos.

 Auto-Relacionamento, quando um mesmo CE desempenha mais de um papel.

#### AGREGAÇÃO

 Juntar objetos compostos para criar um objeto que tem componentes, pense que temos varias entidades, a partir dessas entidades, se surgir algum caso que precise de de todas essas x identidades, podemos junta-las e criar uma nova.

 Agregação de Atributos nos CEs:
  Onde os valores dos atributos compõe a entidade.

 Agregação de CE e CR
 Combina entidades relacionadas e compõe entidades agregadas, também é denominada com como **ENTIDADE ASSOCIATIVA**
 Prestar atenção que as vezes, quando é feito uma agregação de CEs, algum dos atributos de um relacionamento podem ser melhores alocados para essa nova entidade criada, passando assim a serem atributos da nova entidade.

Agregações são geradas de somente um CR.

#### GENERALIZAÇÃO

 Se muitas classes tiverem atributos em comum, podemos fazer uma entidade genérica para que outras entidades herdem atributos delas, exemplo:
 Temos em um caso, alunos, professores, funcionários, todos tendo atributos em comum como, nome, endereço, cpf etc. Nesse caso é mais interessante criar um **SUPERTIPO**, classe que será "pai" dessas outras. Então criamos a entidade "**pessoa**" e fazemos o relacionamento dela com as outras.
 ![[Pasted image 20250414153707.png]]

#### HERANÇA 

CEs específicos herdam todos os atributos do CE genérico.
CEs específicos herdam todos relacionamentos do seu supertipo
Não impede dos CEs específicos terem atributos diferentes 
![[Pasted image 20250414154102.png]]
    - 

#### EXCLUSÃO MÚTUA 

![[Pasted image 20250414175221.png]]

#### SOBREPOSIÇÃO  

![[Pasted image 20250414175204.png]]

#### ESPECIALIZAÇÃO TOTAL 

![[Pasted image 20250414175529.png]]

#### ESPECIALIZAÇÃO PARCIAL 

![[Pasted image 20250414175631.png]]









---
# CITAÇÕES E COMENTÁRIOS
