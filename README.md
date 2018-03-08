# Ruby-learning
Learn and practice Ruby language

Tipos de dados
Não existem "tipos primitivos" em Ruby; todos os tipos são classes:

Object é a classe mãe de todas as outras classes em Ruby
Numeric é uma classe abstrata que representa números
Integer é uma classe que representa números inteiros
Fixnum representa números inteiros de precisão fixa
Bignum representa números inteiros de precisão infinita, dependente apenas da memória disponível
Float é uma classe que representa números de ponto flutuante (números reais)
String uma cadeia de caracteres. Pode ser delimitado por apóstrofes (') ou aspas ("). Tudo o que há entre apóstrofes é interpretado literalmente, entre aspas o programador deve se utilizar de símbolos para representar caracteres específicos, como em C. Exemplos: 'azul', "a\nb\nc"
Symbol é semelhante a uma string, mas dois símbolos iguais possuem o mesmo endereço de memória, sendo assim é ótimo para se utilizar como índice numa Hash. Porém, devido à sua natureza, o coletor de lixo do Ruby não os elimina. É definido com um sinal de dois pontos (:), por exemplo, :nome
Array são arrays dinâmicos, que podem ser usados para representar matrizes e vetores. É delimitado por colchetes ([]) e cada valor é separado por vírgula. Exemplo: [4, 'azul', :termometro]
Hash representa um vetor associativo, e, assim como as Arrays, é dinâmica. É delimitada por chaves ({}), e o índice precede o valor com um sinal '=>'. Exemplo: {:controller => 'user', :action => 'index'}. Qualquer objeto pode ser um índice, mas os mais usados são as Strings e os Symbols
Regexp representa expressões regulares, delimitadas por //. Funciona de forma semelhante a Perl. Exemplo: /a|ae/
