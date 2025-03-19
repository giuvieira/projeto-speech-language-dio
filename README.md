# Análise de Sentimentos e Transcrição de Fala com Azure AI

## Desafio DIO — Speech and Language no Microsoft Azure AI

Neste exercício, utilizei os recursos disponíveis no [Azure Speech Studio](https://speech.microsoft.com/portal) e no [Azure Language Studio](https://language.cognitive.azure.com/tryout/sentiment) para explorar e aplicar as ferramentas de inteligência artificial da Microsoft e avaliar o desempenho dos modelos de aprendizado de máquina.

Este desafio está relacionado ao conteúdo do curso da [DIO](https://web.dio.me/track/decola-tech-2025) sobre **Decola Tech 2025**, no módulo de Serviços Cloud com foco em IA.

## Processamento de Áudio com Azure Speech Studio

### Arquivo de Áudio Utilizado:
Para testar o serviço de transcrição de fala em texto, utilizei o arquivo de áudio **ma_mellauri_enemy.mp3**, que contém uma fala em francês. O **Azure Speech Studio** foi usado para transcrever o áudio em texto, gerando duas saídas:

- **JSON**: A transcrição detalhada, incluindo o tempo de cada palavra e a confiança do modelo.
- **TXT**: A transcrição simples em texto do conteúdo falado.

Exemplo de texto transcrito (em francês):

```txt
T'es la meilleure chose qui m'est arrivé, mais aussi la pire chose qui m'est arrivé ce jour où je t'ai rencontré. J'aurais peut-être préféré que ce jour ne soit jamais arrivé.
```

# Análise de Sentimentos com Azure Language Studio

Neste exercício, utilizei o **Azure Language Studio** para realizar uma análise de sentimentos em um trecho do livro **"O Processo"**, de Franz Kafka, que foi traduzido para o russo.

## Texto Utilizado

O trecho escolhido do livro de Kafka foi o seguinte:

```txt
Кто-то стучал в дверь. Он не знал, кто это, но почувствовал с неприятным предчувствием, что это должен быть кто-то очень важный. Он быстро встал, надел халат и побежал к двери. Уже стоя перед ней, он на мгновение остановился, прежде чем открыть. Что-то заставило его замереть. Чувство неопределенности охватило его, ощущение, что он может делать что-то неправильное, но он уже принял решение. Он открыл дверь.
```
> Tradução

```txt
"Alguém estava batendo à porta. Ele não sabia quem, mas sentiu, com um pressentimento desagradável, que deveria ser alguém muito importante. Levantou-se rapidamente, vestiu o roupão e correu até a porta. Já estava em frente, mas hesitou por um momento, antes de abrir. Algo o fez parar. Uma sensação de incerteza o invadiu, uma sensação de que poderia estar fazendo algo errado, mas ele já havia decidido. Abriu a porta."
```

## Processo de Análise

O **Azure Language Studio** foi utilizado para identificar o sentimento do texto acima, considerando o tom emocional subjacente e classificando o texto em uma das seguintes categorias:

- **Positivo**
- **Negativo**
- **Neutro**

A análise de sentimentos ajuda a identificar como o texto pode ser percebido emocionalmente, o que é útil para compreender melhor a reação dos leitores e a interpretação do conteúdo.

### Resultado da Análise de Sentimentos:
A análise do trecho de Kafka indicou que o **sentimento é negativo**. O texto transmite uma sensação de **insegurança**, **ansiedade** e **dúvida**. O personagem está em um dilema interno, com a sensação de estar tomando uma decisão importante, mas também com um pressentimento de que pode estar cometendo um erro. O tom de incerteza e medo é claro no trecho, refletindo a natureza angustiante da situação descrita.

## Conclusão

Este projeto explorou a transcrição de fala em texto e a análise de sentimentos utilizando as ferramentas **Azure Speech Studio** e **Azure Language Studio**. O **Azure Speech Studio** proporcionou uma transcrição precisa do áudio, enquanto o **Azure Language Studio** foi utilizado para analisar o sentimento do trecho do livro, oferecendo insights valiosos sobre o conteúdo.

