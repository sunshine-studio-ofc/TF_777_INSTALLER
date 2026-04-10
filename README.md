TF777 Robot Framework
O TF777 Robot e uma solucao completa para automacao e processamento de dados, integrando ferramentas poderosas como Python, FFmpeg e Node.js em um ambiente unificado e de facil instalacao.

Descricao do Projeto
Este repositorio contem o nucleo do robo e seu instalador inteligente. O objetivo e fornecer uma experiencia "one-click" para configuracao de ambientes complexos no Windows, garantindo que todas as dependencias sejam instaladas corretamente na pasta local do usuario (AppData).

Funcionalidades Principais
Instalacao Automatizada: Script hibrido que configura Python, Node.js e FFmpeg via Winget.

Interface Grafica (GUI): Instalador moderno com terminal de log em tempo real e barra de progresso.

Gerenciamento de Dependencias: Instalacao automatica de bibliotecas como OpenCV, CustomTkinter, PyGame e Google Generative AI.

Isolamento de Sistema: O sistema e instalado em %APPDATA%\.tf777, evitando poluir as pastas padrao do Windows.

Pre-requisitos
O instalador foi projetado para sistemas Windows 10 ou 11, pois utiliza o gerenciador de pacotes Winget nativo da Microsoft.
Alem do hardware feito em arduino.
Que esta aqui e na releases.

Como Instalar
Faca o download do arquivo TF777_Setup.EXE na aba [Releases].

Execute o instalador como Administrador (necessario para instalar Python e Node.js).

Aceite os termos de uso na primeira tela.

Aguarde o processamento do Log no Terminal interno.

Apos a conclusao, um atalho sera criado automaticamente na sua Area de Trabalho.

Componentes Instalados
O framework utiliza as seguintes tecnologias:

Python 3.11: Engine principal do robo.

FFmpeg: Para manipulacao de arquivos de audio e video.

Node.js: Para suporte a scripts de backend.

Bibliotecas Python: customtkinter, google-generativeai, pygame, gTTS, SpeechRecognition, yt-dlp, pyserial, opencv-python.

Estrutura de Pastas
Apos a instalacao, a estrutura sera:

Plaintext
%APPDATA%\.tf777\
  ├── iniciar.exe       # Binario principal
  ├── scripts\          # Logica do robo
  ├── assets\           # Arquivos de midia e icones
  └── config\           # Arquivos de configuracao local
Seguranca e Antivirus
Este projeto utiliza scripts de automacao que podem ser detectados como falsos-positivos por alguns antivirus (ex: Kaspersky, Windows Defender) devido a natureza da instalacao automatizada. Caso ocorra um bloqueio:

Clique em "Mais Informacoes".

Selecione "Executar assim mesmo".

Adicione a pasta %APPDATA%\.tf777 as exclusoes do seu antivirus.

Desenvolvedor
Sunshine Studio
