

------------
###  Metodo 1: Tradução via SDK Renpy

> Metodo mais simples é rapido de ser ultilizado, porem a busca pelos textos e feita pelo proprio SDK ou seja isso pode fazer com que algumas palavras fiquem no idioma original.

##### Requisitos:
- [Translator++](https://dreamsavior.net/download/ "Translator++")
- [SDK Ren`Py](https://www.renpy.org/latest.html "SDK Ren'Py")
- Qualquer Ferramenta de Extração ([Unren](https://f95zone.to/threads/unren-v-0-11v3-unren-v-0-12v3-unren-v-0-13-v2-unren-windowed.92717/ "Unren"))
> Vou ultilizar o Unren, entretanto qualquer ferramenta de extração de arquivos rpa pode ser ultilizada, [GARBRO](https://github.com/morkt/GARbro "GARBRO") por exemplo.

[========]

##### Extração de aquivos
A ferramenta funciona somente se você extrar os arquivos internos do jogo, não pode ter nenhum arquivo .rpa ou qualquer tipo de compactação dentro do arquivo.
> Você precisa baixar unren.bat correspondente a versão do seu jogo

###### Então seguindo essa logica:

**UnRen v.0.12** -- para versão 7.4.7+
**UnRen v.0.13** -- apenas para jogos RenPy 8+
**UnRen v.0.11** -- para versão 7.4-

Você pode encontrar a versão do seu jogo de 3 maneiras diferentes.
- Dentro da pasta game muitas vezes existe um arquivo chamado **script_version.txt**, abrindo ele você tem a numeração da sua versão.
- Ao abrir o jogo, ele pode gerar um arquivo chamado **log.txt**, dentro dele apos a palavra Ren´Py tem a numeração da sua versão.
- Em ultimos caso você pode renomear a pasta game para game2 e abrir o seu jogo, isso irá gerar um arquivo de erro chamado **traceback** no final deste documento tem a versão do jogo. 

##### Observações:

Alguns jogos podem ter seu codigo fonte encriptado ou mesmo o desemvolvedor pode ter dificultado a modificação de seu jogo, esse metodo somente irá funcionar se você conseguir realizar a extração dos arquivos de forma correta.

> Burlando esses mecanimos caso eles existam no jogo que você quer traduzir.

##### Passoa a Passo:

1. Extraia o jogo que você deseja traduzir em uma pasta qualquer ou entre na pasta do jogo.

