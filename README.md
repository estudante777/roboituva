# RoBoiTuva

O projeto visa viabilizar o ensino de robótica e programação tanto para os alunos do IFSP Campus de Boituva quanto para os membros interessados da comunidade.

## Visão geral

Neste manual você encontrará tudo o que você precisa para dar os seus primeiros passos no mundo da programação e robótica.
Iremos instalar os softwares que utilizaremos durante os enconstros presenciais e tutoriais que estão no nosso canal oficial e no canal dos instrutores.

## Pré-requisitos

Realize o download das seguintes ferramentas e arquivos:

- [Visual Studio Code](https://code.visualstudio.com/download) (VSCode)
- [Balena Etcher](https://etcher.balena.io/#download-etcher) (Etcher)
- [EV3 MicroPython micro SD card image](https://education.lego.com/en-us/product-resources/mindstorms-ev3/teacher-resources/python-for-ev3/) (Firmware oficial que permite a utilização de MicroPython no EV3)


## Instalação

Instale o Visual Studio Code e o Balena Etcher em seu computador.

Caso tenha alguma dificuldade ou não esteja se sentindo tão confiante assista ao vídeo que gravamos o passo a passo.

- [Tutorial de Instalação dos Softwares Necessaŕios](https://)

Com todos os softwares instalados iremos extrair o arquivo zip que baixamos contendo o firmware do bloco EV3.
Após a extração você terá um arquivo **.iso**, utilizaremos esse arquivo no Etcher.

Plugue o micro SD ao computador utilizando um adaptador.

Abra o Etcher clique na opção *Flash from file* e selecione o arquivo *.iso* que acabou de extrair, após isso clique em *Select target* e escolha o micro SD e por último clique em *Flash* e aguarde a instalação. Quando o processo terminar, remova o micro SD do computador e insira-o no EV3.
Com o micro SD dentro do bloco, ligue-o e aguarde a inicialização do sistema operacional, durante o processo de boot você notará que os leds do bloco estarão piscando em laranja e haverá bastante texto no visor, isso é normal.

## Pós-instalação

Após a instalação dos programas necessários e do firmware no bloco EV3 iremos realizar a instalação de uma extensão no VSCode chamada LEGO® MINDSTORMS® EV3 MicroPython.

Clique no link abaixo para ir até a página oficial da extensão.

- [Extensão LEGO MIDSTORMS](https://marketplace.visualstudio.com/items?itemName=lego-education.ev3-micropython)

Com a extensão instalada e o EV3 ligado iremos conectá-lo ao computador através de um cabo usb.
O dispositivo será reconhecido no computador e no VSCode, a partir disso poderemos iniciar o desenvolvimento dos programas em código MicroPython.

## Autores

- Marcelo Frate - Professor Doutor - [Lattes](http://lattes.cnpq.br/8632724748282199)
- Emerson J. - Monitor de Robótica e Programador - [LinkedIn](https://www.linkedin.com/in/%C3%A9merson-j%C3%BAnior-a3b216214/)
- Mateus de Melo - Programador - [LinkedIn](https://www.linkedin.com/in/mateusdemelo/)

## Licença

Este projeto está licenciado sob a licença [MIT](https://mit-license.org/)

## Agradecimentos

  - Agradecemos a todos os participantes do projeto e a todos aqueles que foram beneficiados de alguma forma com os trabalhos que desenvolvemos.