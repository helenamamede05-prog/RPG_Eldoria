# RPG — A Jornada de Eldoria

Abra a pasta `RPG_Eldoria` no IntelliJ IDEA, selecione um JDK 17 ou superior se necessário e inicie **Executar** ou o método main de `rpg.test.JogoTest01`.

O herói começa com 100 pontos de vida, 15 de ataque, 5 de defesa, 30 de ouro e duas poções. O jogo passa pela Floresta Sombria, pela Caverna dos Ossos e pelo Castelo das Sombras. Após cada vitória, o jogo distribui ouro e experiência e libera a etapa seguinte.

As classes do jogo ficam em `rpg.dominio`. As demonstrações e verificações executáveis ficam em `rpg.test`. Execute `rpg.test.JogoQATest01` para reproduzir os dez cenários integrados. Os testes de poção, loja, referências, batalha e nível também podem ser executados individualmente.

Os preços e as recompensas foram definidos dentro da margem deixada pelo enunciado. O inventário conta poções em uma pilha, e o jogo interativo vende e usa a Poção Pequena. A Poção Grande é exercitada na classe `PocaoTest01`.
