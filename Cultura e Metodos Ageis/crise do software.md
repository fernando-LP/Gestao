# Caminho da Crise de Software

A crise de software surgiu por alguns motivos, como atrasos nas entregas, custos exorbitantes, baixa qualidade, mas principalmente pelos atrasos e bugs generalizados nos projetos de desenvolvimento. O termo foi criado em 1970 pelo engenheiro Roger Pressman.

Naquela época, iniciaram-se alguns estudos para resolver a crise de software e contornar esses problemas. Abaixo, veremos as técnicas utilizadas:

## Abordagem Estruturada

A principal ideia da abordagem estruturada era dividir o projeto de software em pequenas entregas, para haver mais controle ao agregar várias partes simples.

O problema dessa abordagem era que existiam muitas partes do software criadas. Até certo nível de desenvolvimento, por exemplo, níveis 1 e 2, era possível manter dessa forma. Mas a partir desse ponto, surgiam muitas variáveis e uma infinidade de partes, o que dificultava a composição do todo.

## Orientação a Objetos

O objetivo principal dessa abordagem era reaproveitar códigos, torná-los mais autônomos, com um melhor reaproveitamento. Um objeto é uma estrutura de software que contém dados, funções e métodos compactados dentro de uma estrutura autônoma, permitindo que funcione de forma independente.

A orientação a objetos ainda é amplamente utilizada no desenvolvimento de software. Para entender a fundo seu funcionamento, seria necessário uma aula de programação, onde compreenderíamos como um código pode ser independente de outro. Por exemplo, ao criarmos uma lista de compras, podemos querer saber a quantidade de produtos no total. A lógica para contar a quantidade será a mesma para qualquer lista. Assim, criamos uma função dentro de um objeto que pode ser usada em qualquer lista de compras, sendo chamada a qualquer momento.

Até hoje, a orientação a objetos é utilizada, mas não resolveu completamente a questão do reaproveitamento.

## Engenharia de Software

Com os estudos, percebeu-se que na construção de prédios ou casas havia engenheiros acompanhando a obra, e, apesar das diferenças entre os prédios, algumas partes seguiam a mesma lógica, como as paredes.

Nesse sentido, notou-se que faltava disciplina de engenharia na indústria de software. Assim, foram trazidas práticas de engenharia para o desenvolvimento, especialmente na gestão de projetos.

## Projetização do Desenvolvimento

Outro ponto pensado foi que a crise de software ocorria pela falta de planejamento. Na engenharia, antes de iniciar uma construção, realiza-se um planejamento detalhado, como a altura, comprimento e largura de paredes, lajes, etc.

Assim, foram trazidas práticas da engenharia tradicional para o desenvolvimento de software, buscando tornar o processo mais previsível.

## Engenharia Tradicional

A engenharia tradicional e projetos civis lidam com produtos complicados, mas repetitivos e previsíveis. Para construir um prédio, por exemplo, já existe uma "receita". O mesmo vale para construir um navio.

Porém, no desenvolvimento de software, a emulação da engenharia não resolveu o problema, pois **o software é um produto complexo**, ou seja, não é repetitivo nem previsível. Seu escopo não pode ser completamente definido antes de ser utilizado, sendo descoberto ao longo do desenvolvimento.

## Waterfall (Cascata)

O método waterfall, ou cascata, é aplicado a produtos complicados, mas não aos complexos. Ele segue a seguinte estrutura:

1. Definir o escopo detalhado de todo o produto.
2. Criar documentação em forma de especificações funcionais e técnicas.
3. Construir o produto de uma só vez ou em grandes entregas.
4. Testar tudo de uma vez ou em grandes partes.
5. Fazer a implementação de uma só vez ou com grandes entregas espaçadas no tempo.

Com essa abordagem, acreditava-se que os softwares seriam entregues com mais previsibilidade e menos problemas. No entanto, essa metodologia não apresentou bons resultados no desenvolvimento de software.

### Participação Restrita de Pessoas e Usuários

A participação dos stakeholders ocorre no início do projeto, na definição do escopo, e no final, durante a entrega. Porém, a equipe de desenvolvimento "desaparece" por um tempo, às vezes um ou dois anos, entregando no final um software pronto, ou fazendo grandes entregas a cada seis meses, por exemplo.

Esse longo período sem contato com os usuários que de fato utilizarão o produto pode gerar um descompasso com as necessidades. Novas ideias podem surgir, e quando o
