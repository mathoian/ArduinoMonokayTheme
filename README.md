


Tema Monokay Arduino IDE 1.8.5
S.O Arch linux x64


O tema é um pasta contendo as imagens, arquivos e ítens necessários para compilação

Antes de trocar os arquivos é necessário checar a versão da IDE do Arduino.

Criei os passos trocando apenas os arquivos, para esse tutorial ficar genérico.

Segue os passos para personalizar a IDE do Arduino:


(((((( No linux ))))))

Serão usados dois arquivos basicamente, default.xml e theme.txt

O passo inicial é mudar para usuário root porque provávelmente o usuáro comum não poderá renomear os arquivos necessários

Não apague os arquivos originais para caso necessite ou queira voltar ao modo original.

Faça o Download dos arquivos

1 - mude seu usuário para root

2 - acesse a pasta /usr/share/arduino

3 - dentro da pasta acima existe uma pasta chamada lib que contém a pasta theme /usr/share/arduino/lib/theme

dentro da pasta possui o arquivo theme.txt, renomei o arquivo(ex: theme_original.txt) e cole o theme.txt do download (o original

é para  caso queira retornar ao estilo original)

5 - dentro da pasta tmeme existe uma pasta chamada syntax que contém o arquivo default.xml /usr/share/arduino/lib/theme/syntax

o mesmo processo do arquivo theme.txt, renomei o arquivo original da pasta (eu uso sempre syntax_original.xml) e cole o 
default.xml do download


6 - Restart a IDE

Caso não funcione vc pode desfazer. Lembra dos arquvos originais? renomei novamente e tudo deve voltar ao normal



(((((( No windows ))))))

Apenas alguns passos são diferentes, referente ao root que não existe no Win. e o acesso as pastas que estão listadas abaixo.

1 - acesse C:\Program Files (x86) \ Arduino \ lib \theme

2 -  renomei o arquivo original

3 -  cole o arquivo theme.text

4 acesse a pasta  C:\Program Files (x86) \ Arduino \ lib \theme \syntax

5 - renomei o arquivo original default.xml

6 - cole o arquivo que foi baixado default.xml

7 Restart IDE

Caso seja a mesma versão do exemplo Arduino IDE 1.8.5 deixei a pasta da minha IDE.

Caso não funcione vc pode  Lembra dos arquvos originais? renomei novamente e tudo deve voltar ao normal



## Outros temas - outras versões IDE ##

  Jeff Thompson https://github.com/jeffThompson/DarkArduinoTheme
  
  Monokai Styling  Technobly https://github.com/technobly/MonokaiArduinoTheme
