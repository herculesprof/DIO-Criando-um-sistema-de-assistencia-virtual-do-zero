# Sistema de Assistência Virtual com PLN

Este projeto consiste na criação de uma assistente virtual desenvolvida em Python no Google Colab, integrando processamento de linguagem natural (PLN) e automação.

## 📋 Requisitos do Projeto
O sistema foi desenvolvido para atender aos seguintes critérios:
1.  **Módulo Text-to-Speech:** Converte as respostas de texto da assistente em áudio utilizando a biblioteca `gTTS`.
2.  **Módulo Speech-to-Text:** Capaz de transcrever a fala humana em texto.
3.  **Comandos de Voz Automatizados:** Acionamento de funções como pesquisas no Wikipedia, abertura de plataformas (YouTube) e localização de serviços (farmácias).

## 🛠️ Tecnologias Utilizadas
- **Python 3** no ambiente Google Colab.
- **gTTS (Google Text-to-Speech):** Para síntese de voz.
- **SpeechRecognition:** Para reconhecimento de fala.
- **Wikipedia API:** Para consultas automatizadas de informações.

## 🚀 Como Funciona
A assistente processa a entrada de áudio do usuário, identifica palavras-chave (comandos) e executa ações específicas. O processamento é feito de forma híbrida, utilizando JavaScript para captura de áudio no navegador e Python para a lógica de PLN.

## 📌 Links de Referência
O projeto baseia-se nos exemplos de Text-to-Speech e Speech-to-Text disponibilizados pela DIO.
