# Análise de Imagens Azure Vision

Este projeto consiste na utilização de três diferentes modelos de Inteligência Artificial disponibilizados pela Microsoft Azure Vision AI para analisar imagens.

## Modelos Utilizados

### OCR (Reconhecimento Óptico de Caracteres)
O modelo de OCR é responsável por extrair texto de imagens.

### Detecção de Rostos
Este modelo é capaz de detectar e marcar rostos em imagens.

### Geração de Legendas
O modelo de geração de legendas analisa a imagem e fornece uma descrição contextualizada.

## Insights

### OCR
- Letras muito pequenas e textos em fontes detalhadas podem dificultar o reconhecimento.
- Imagens embaçadas podem prejudicar a precisão da extração de texto.
- Útil para automatizar tarefas de tradução, desde que a imagem seja clara e o texto legível.

### Detecção de Rostos
- Em imagens com muitas pessoas, pessoas ao fundo podem ser erroneamente marcadas como usando máscaras.
- Funciona bem em ambientes organizados, mas pode ter dificuldades em ambientes confusos com muitas pessoas.

### Geração de Legendas
- Pode falhar em capturar detalhes importantes da cena, como expressões faciais ou objetos específicos.
- Tende a generalizar descrições em imagens com muitas pessoas ou elementos.

## Screenshots (Opcional)

Screenshots de algum dos outputs:

![screenshot_1](screenshots\ss1.png)


![screenshot_2](screenshots\ss2.png)


![screenshot_3](screenshots\ss3.png)