# Functional-Light JavaScript
# Prefácio

> *Uma mônada é apenas um monóide na categoria de endofunctors.*

Você não entendeu? Não se preocupe, eu também estaria perdido! Todos aqueles termos que só significam algo para aqueles que já são iniciados em Programação Funcional&trade; (PF) são apenas bobagens confusas para muitos de nós.

Este livro não vai te ensinar o que essas palavras significam. Se é isso que você está procurando, continue procurando. Na verdade, já existem muitos excelentes livros que ensinam o PF *da maneira certa*, de cima para baixo. Essas palavras têm importantes significados e se você estudar PF em profundidade, com certeza vai querer se familiarizar com elas.

Mas este livro abordará o assunto de maneira bem diferente. Apresentarei conceitos fundamentais de PF desde a base, com menos termos especiais ou não intuitivos do que a maioria das abordagens de PF.Nós tentaremos adotar uma abordagem prática para cada princípio, em vez de um ângulo puramente acadêmico. **Haverá termos**, sem dúvida. Mas seremos cuidadosos e ponderados ao apresentá-los e explicar por que são importantes.

Infelizmente, não sou um membro do clube de crianças legais da PF. Nunca fui formalmente ensinado nada sobre PF. E embora eu tenha formação acadêmica em ciência da computação e tenho um nivel decente em matemática, a notação matemática não é a forma como meu cérebro entende programação. Nunca escrevi uma linha de Scheme, Clojure ou Haskell. Não sou um Lisp'r da velha guarda.

Eu *já* participei de inúmeras conferências sobre PF, cada uma com uma desesperada esperança que de finalmente, *desta vez* seria o momento em que eu entendesse do que se trata todo esse misticismo de programação funcional. E a cada vez, ficava frustrado e lembrava que esses termos se misturaram na minha cabeça e não tinha ideia se ou o que havia aprendido. Talvez eu tenha aprendido algumas coisas. Mas eu não conseguia descobrir o que essas coisas eram por muito tempo.

Pouco a pouco, através dessas várias exposições, descobri pedaços de importantes conceitos que parecem vir muito naturalmente para o programador funcional formal. Eu os aprendi lentamente e os aprendi pragmaticamente e experiencialmente, não academicamente com a terminologia apropriada. Você alguma vez já conheceu uma coisa por muito tempo, e só depois descobriu que tinha um nome específico para isso e você nunca soube !?

Talvez você seja como eu; Eu ouvi termos como "map-reduce" em segmentos da indústria como "big data" por anos, sem nenhuma ideia real do que eram. Eventualmente eu aprendi o que a função `map(..)`
fazia -- muito tempo antes eu tinha alguma ideia de que as operações de lista eram a base do caminho do programador funcional, e o que as torna tão importantes. Eu sabia o que era *map* muito antes de saber que se chamava `map(..)`.

Eventualmente, comecei a reunir todos esses pequenos fragmentos de compreensão para o que agora chamo "Functional-Light Programming" (FLP).

## Missão


Mas por que é tão importante que você aprenda programação funcional, até mesmo a forma leve?

Eu passei profundamente a acreditar em algo nos últimos anos, tanto que você poderia *quase* chamar de crença religiosa. Eu acredito que a programação é fundamentalmente sobre humanos, não sobre código. Eu acredito que o código é antes de mais nada um meio de comunicação humana, e apenas como um *efeito colateral* (ouça minha risada autorreferencial) ele instrui o computador.

A meu ver, a programação funcional é fundamental para o uso de padrões em seu código que são bem conhecidos, compreensíveis *e* comprovadamente afastados dos erros que tornam o código mais difícil de entender. Nesse ponto de vista, programação funcional! - pode ser uma das mais importantes coleções de ferramentas que qualquer desenvolvedor pode adquirir.

> A maldição da mônada é que ... uma vez que você entende ... você perde a habilidade de explicá-la para qualquer outra pessoa.
>
> Douglas Crockford 2012 "Monads and Gonads"
>
> https://www.youtube.com/watch?v=dkZFtimgAcM

Eu espero que esse livro "talvez" possa quebrar essa maldição, embora não falemos de "mônadas" até o final nos apêndices.

O programador funcional formal freqüentemente afirma que o *valor real* do PF está em usá-lo essencialmente em 100%: é uma proposição tudo ou nada. A crença é que, se você usar o PF em uma parte do programa, mas não em outra, todo o programa será poluído por coisas não-PF e, portanto, sofrerá o suficiente para que o PF provavelmente não valesse a pena.

Direi de forma inequívoca: **Acho que isso é um absolutismo de araque**. Isso é tão bobo para mim quanto sugerir que este livro só é bom se eu usar gramática perfeita e voz ativa o tempo todo; se eu cometer algum erro, isso prejudicará a qualidade do livro inteiro. Absurdo.

Quanto melhor eu escrever com uma voz clara e consistente, melhor será sua experiência de leitura. Mas não sou um autor 100% perfeito. Algumas partes serão melhor escritas do que outras. As partes que ainda posso melhorar não invalidarão as outras partes deste livro que são úteis.

E assim é com nosso código. Quanto mais você aplicar esses princípios a mais partes do seu código, melhor será o seu código. Use-os bem 25% do tempo e você obterá bons benefícios. Use-os 80% do tempo e você verá ainda mais benefícios.

Com talvez algumas exceções, não acho que você encontrará muitos absolutos neste texto. Em vez disso, falaremos sobre aspirações, objetivos, princípios pelos quais lutar. Falaremos sobre equilíbrio, pragmatismo e trade-offs.

Bem-vindo a esta jornada para os fundamentos mais úteis e práticos da PF. Ambos temos muito o que aprender!
