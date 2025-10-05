O objetivo deste trabalho era a compreensão, design e conceção passo a passo de um conversor de eletrónica de potência, neste caso um conversor CC-CC do tipo boost.

Foi o primeiro conversor desenvolvido pelo grupo na Universidade, e a topologia foi escolhida dada a sua simplicidade. Foram estudados vários conceitos transversais a inúmeros conversores, tais como a variação do duty-cycle e da frequência de comutação e os seus efeitos, a variação dos valores da bobina e do condensador de saída e os seus efeitos, a variação do valor da carga resistiva e problemas associados a duty-cycles de 100% e conversores sem carga. Estes comportamentos foram todos validados em ambiente de simulação (PSIM). Adicionalmente, foi desenhado e concebido um circuito de gate driver não isolado, e o seu comportamento foi avaliado no PSIM e, posteriormente, em ambiente laboratorial. O circuito foi testado em malha aberta, com recurso a um gerador de sinais a dar drive ao circuito de comando. Após validação em breadboard, foi feita uma PCB que contemplava todo o circuito de potência e comando, bem como um microcontrolador ATMega328P que viria a fazer o lugar do gerador de sinais, gerando um PWM capaz de atuar o circuito de comando. Um pequeno LCD foi adicionado para saber a frequência e o duty-cycle durante a operação do conversor.

Neste repositório, é possível encontrar dois ficheiros:

  1. Um PDF que contém todos os testes em simulação e breadboard, e responde a várias perguntas feitas em aula.

  2. Um PPT que apresenta todo o trabalho feito nesta UC, desde as simulações à PCB.

Com este trabalho foi intuitivo aprender sobre o funcionamento de conversores de eletrónica de potência deste tipo, bem como dimensionar circuitos de comando não isolados.
