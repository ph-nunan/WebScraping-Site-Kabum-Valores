# WEBSCRAPPING - EXTRAÇÃO DE VALORES - SITE KABUM

Esse código em Python realiza a tarefa de coletar informações sobre cadeiras gamers do site "https://www.kabum.com.br/cadeiras/cadeiras-gamer" usando web scraping e, em seguida, armazena esses dados em um arquivo CSV. 




## VISÃO GERAL

### Propósito

Este projeto consiste em um script em Python que realiza a raspagem de dados do site da Kabum, focando em cadeiras gamers. O objetivo principal é coletar informações detalhadas sobre várias cadeiras gamers disponíveis no site, como marcas e preços, e organizar esses dados em um formato estruturado.

### Problema Resolvido

O problema que o projeto aborda está relacionado à conveniência e eficiência na comparação de cadeiras gamers. Com uma grande variedade de opções disponíveis no mercado, os consumidores muitas vezes enfrentam dificuldades ao buscar informações detalhadas sobre diferentes modelos e preços. Esse projeto oferece uma solução ao automatizar o processo de coleta de dados, permitindo que os usuários comparem rapidamente as opções disponíveis e tomem decisões de compra mais informadas.

### Público-Alvo

O público-alvo desse projeto inclui entusiastas de jogos, profissionais de eSports e qualquer pessoa que esteja interessada em adquirir uma cadeira gamer de qualidade. Ao fornecer uma compilação abrangente de informações em um formato organizado, o projeto simplifica o processo de pesquisa e ajuda os usuários a identificar as melhores opções de cadeiras gamers de acordo com suas preferências e orçamento.


## CAPTURAS DE TELA

![scrapping kabum exe](https://github.com/ph-nunan/WebScrapping-Site-Kabum-Valores/assets/117214802/9f419488-1520-4fc3-8cd3-1147f47b6c08)


## FUNCIONALIDADES PRINCIPAIS

###  Coleta de Dados Automatizada: 
O script automatiza o processo de coleta de informações sobre cadeiras gamers, eliminando a necessidade de realizar pesquisas manuais em diversas páginas.

###  Informações Detalhadas: 
O projeto extrai dados detalhados sobre cada cadeira gamer, incluindo a marca e o preço. Isso oferece uma visão completa das opções disponíveis.

###  Comparação Simples:
Os dados coletados são organizados em uma estrutura tabular (DataFrame), o que facilita a comparação entre diferentes cadeiras gamers em termos de marca e preço.

### Eficiência na Pesquisa:
Usuários podem examinar rapidamente várias cadeiras gamers sem a necessidade de navegar pelo site manualmente, economizando tempo e esforço.

###  Decisões Informadas:
Ao ter acesso a informações detalhadas e estruturadas, os usuários podem tomar decisões de compra mais informadas, considerando várias opções e preços.

###  Exportação de Dados:
O projeto gera um arquivo CSV contendo os dados coletados, permitindo que os usuários salvem as informações para referência futura ou análises adicionais.

###  Customização de Busca:
O script pode ser facilmente adaptado para buscar outros detalhes além de marca e preço, fornecendo flexibilidade para aprimoramentos futuros.

###  Reutilização:
O código pode ser reutilizado para realizar raspagens similares em outros sites de compras, simplificando a obtenção de informações de produtos de diferentes origens.

- Essas funcionalidades em conjunto oferecem aos usuários uma ferramenta poderosa para pesquisar, comparar e tomar decisões embasadas na escolha da cadeira gamer ideal para suas necessidades e preferências.





## TECNOLOGIAS UTILIZADAS

- Python

###  Bibliotecas e Frameworks:

- #### requests:
  
  Usada para fazer requisições HTTP para o site da Kabum.

- #### BeautifulSoup:
  
  Utilizada para analisar o HTML das páginas e extrair informações.

- #### re (expressões regulares):
  
   Usada para trabalhar com padrões de texto e extrair informações específicas.

- #### pandas:
  
  Utilizada para manipular os dados em formato tabular (DataFrame) e exportá-los para um arquivo CSV.

- #### math:
  
  Utilizada para realizar cálculos matemáticos, como o arredondamento para cima.

### Tecnologias Adicionais:

- #### User-Agent:
  
  Um cabeçalho HTTP personalizado utilizado para simular um navegador ao fazer requisições HTTP, evitando bloqueios por parte do site.

- #### HTML:
  
  A linguagem de marcação utilizada para estruturar o conteúdo das páginas da web, que é analisada pelo BeautifulSoup.





## PRÉ-REQUISITOS

- Python:

O projeto é construído em Python, portanto, é necessário ter o Python instalado na máquina. Você pode baixar o Python em https://www.python.org/downloads/.
Bibliotecas:

Certifique-se de ter as seguintes bibliotecas instaladas no ambiente Python:

- #### requests

- #### beautifulsoup4

- #### pandas

Você pode instalar essas bibliotecas usando o gerenciador de pacotes pip com os seguintes comandos:

```bash

pip install requests
pip install beautifulsoup4
pip install pandas
```



## OBSERVAÇÕES

- Dependendo do sistema operacional, você pode precisar usar o comando python3 em vez de python para iniciar o interpretador Python.

- O script irá imprimir no terminal as marcas e os preços das cadeiras gamers enquanto percorre as páginas do site.

- O arquivo CSV contendo os dados coletados será salvo na pasta onde o script está localizado.

- Certifique-se de que a pasta onde o arquivo CSV será salvo tenha permissões de escrita.



## AUTOR

Paulo Nunan



## LICENÇA

MIT




## AGRADECIMENTOS

Conhecimento adquirido através dos cursos: Alura, CodeAcademy,youtube + faculdade de Eng. de Software.
