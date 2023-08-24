# Livro BM Atividade I pag 23

- Questão 01 -A função principal da Máquina Virtual Java (JVM) é executar programas escritos em Java, agindo como um intermediário entre o código Java e o sistema operacional. Ela oferece portabilidade, gerenciamento de memória, gerenciamento de threads, segurança e otimização de desempenho, permitindo que os programas Java sejam executados em diferentes plataformas de maneira eficiente e segura. Esse recurso garantiu a popularidade de Java pois permite executar em qualquer lugar um código já escrito, pois a JVM executa o bytecode gerado a partir do código gerado em um arquivo .java.

- Questão 2 - O JRE é apenas o ambiente padrão para usuários comuns, contém apenas o necessário para executar aplicações em Java, o JDK é a versão para desenvolvedores, o próprio JRE está (tecnicamente) contido aqui, pois além do ambiente de execução possui também ferramentas para criar programas em Java.

- Questão 3 - Veja arquivo BmAtividade3.java.

- Questão 4 - Dado que a IDE o arquivo .java é transformado no arquivo .class composto pelo bytecode que é o que a JVM interpreta, ao apagar o arquivo .class o código exibe mensagem de erro pois o arquivo .java não é lido pela JVM. dado que eu usei a IDE eu até esperava que um outro arquivo .class fosse gerado automaticamente, mas não ocorreu.

- Questão 5 - Após fazer a implementação do codígo fazendo a troca do main por start ao compilar ocorreu tudo normalmente. O ponto é que o nome do método não é relevante desde que seja construído como o método main normalmente é construído, utilizando "String[] args" como parâmetros.

- Questão 6 - Ver arquivo BmAtividade6.java.

- Questão 7 - Após fazer a implementação do codígo e compilar, aparece a seguinte mensagem "class, interface, enum, or record expected", como Java é case sensitive então escrever palavras chave em maiúsculo resulta em erro.

- Questão 8 - Como o nome da classe foi alterado no código então houve um erro na hora de executar, o compilador não podia saber qual arquivo deveria executar devido ao erro na diferença dos nomes.
