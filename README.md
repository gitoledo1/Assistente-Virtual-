# Assistente-Virtual-
Este projeto implementa um assistente virtual que utiliza Processamento de Linguagem Natural (PLN) para compreender comandos de voz e executar ações automatizadas. Ele é capaz de:

Transcrever áudio em texto usando o modelo Whisper da OpenAI.

Executar comandos baseados em voz, como:

Pesquisar tópicos no Wikipedia

Abrir o YouTube

Localizar a farmácia mais próxima (link do Google Maps)

Responder com voz (Text-to-Speech) usando a biblioteca pyttsx3.

O projeto foi desenvolvido em Python e pode ser executado tanto localmente quanto em Google Colab, utilizando arquivos de áudio previamente gravados (formato WAV).

Funcionalidades

Text-to-Speech (TTS): converte texto em áudio para simular a fala do assistente.

Speech-to-Text (STT): reconhece comandos de voz a partir de arquivos WAV.

Execução de comandos automáticos: pesquisa, navegação na web e consultas rápidas.

Tecnologias utilizadas

Python 3.x

OpenAI Whisper

pyttsx3

Wikipedia API

Webbrowser (para abrir links)

Como usar

Grave um áudio em WAV com seu comando de voz.

Execute o script Python localmente ou no Google Colab.

O assistente vai transcrever o áudio e executar a ação correspondente.
