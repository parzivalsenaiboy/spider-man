# Spider-Man Swing — Minecraft Forge 1.20.1

Primeiro protótipo de web swing inspirado na movimentação de Spider-Man (PS4).

## Requisitos
- Minecraft Java Edition 1.20.1
- Minecraft Forge 47.2.0
- Java JDK 17
- Gradle wrapper (gerado na primeira configuração, ou use Gradle instalado)

## Controles
- Segure **G** mirando em um bloco para lançar uma teia e balançar.
- Solte **G** para soltar a teia e manter o impulso.

A teia deste protótipo ancora em blocos que o jogador consegue mirar a até 40 blocos.
A linha visual da teia e animações do traje ainda não estão incluídas nesta primeira versão.

## Compilar
No diretório do projeto, com Gradle instalado:
```bash
gradle genEclipseRuns
gradle build
```
O arquivo compilado será criado em `build/libs/spidermanswing-1.0.0.jar`.

Para desenvolvimento, importe a pasta no IntelliJ IDEA ou Eclipse como projeto Gradle.
Se não tiver Gradle instalado, gere o wrapper com `gradle wrapper --gradle-version 8.1.1`.

## Observações
Este é um protótipo inicial. A física usa uma restrição de comprimento de corda e projeção da velocidade radial; não é uma cópia exata da física proprietária do jogo de PS4.
