# Heavy Metal Analysis

![](https://img.shields.io/badge/Python-3.8-blue.svg)
![](https://img.shields.io/badge/Pandas-blue.svg)
![](https://img.shields.io/badge/Matplotlib-blue.svg)
![](https://img.shields.io/badge/nltk-blue.svg)

<img src="http://pm1.narvii.com/6703/2dc363645561bfb92fad0963d15437e5d0400391_00.jpg">

Projeto de estudo de letras de músicas de Heavy Metal. Analise quantas músicas uma banda tem, frases e palavras mais usadas nas letras.

Crie gráficos, nuvem de palavras.

### Como configurar o ambiente

- crie um virtual env
- instale as dependências
- crie uma chave na API da Last FM
- copie o .env_sample para .env e informe suas credenciais
- rode o Jupyter Lab

### Criar um Virtual Environment


### Instalar as dependências

Abra um terminal, ou command ( Windows), ative o virtual env e rode o comando abaixo.

```pip install -r requirements.txt```


### Crie uma chave na API da Last.FM

[Documentação da API Last.FM](https://www.last.fm/api/intro)


### Copie o .env_sample para .env e informe suas credenciais

```
LAST_FM_KEY=<chave de acesso na API>
LAST_FM_SECRET=<secret de acesso na API>
```


### Rode o Jupyter Lab

Abra um terminal

```jupyter lab```



### Como executar o estudo

- informe o nome da banda na variável ```artist```
- execute o passo a passo do Jupyter


### Fontes

[BeatlesWordCloud](https://github.com/DensonAbraham/BeatlesWordCloud)

[Last.FM API Doc](https://www.last.fm/api)

### TODO

- encontrar uma API para retornar os dados do álbum
- encontrar uma API para retornar as músicas por álbuns