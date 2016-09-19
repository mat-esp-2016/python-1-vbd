# Python 1: variáveis, bibliotecas e gráficos

Parte do curso
[Matemática Especial I](https://github.com/mat-esp/about)
da [UERJ](http://www.uerj.br/).

Ministrado por [Leonardo Uieda](http://www.leouieda.com/).


## Objetivos

* Aprender o que são variáveis e seus tipos básicos no Python.
* Aprender a usar funções internas do Python e de bibliotecas.
* Conseguir ler dados de arquivos simples e fazer gráficos usando o matplotlib.


## Leitura recomendada

Vamos seguir de perto o material
[Programming with Python](http://swcarpentry.github.io/python-novice-inflammation/)
e
[Plotting and programming in Python](http://swcarpentry.github.io/python-novice-gapminder/)
do Software Carpentry.
Farei algumas modificações para ser mais voltado para o tipo de dados que
costumamos encontrar nas geociências.

Uma ótima referência para aprender a usar o numpy e matplotlib é o
[Scipy Lectures](http://www.scipy-lectures.org/).

A [Galeria do matplotlib](http://matplotlib.org/gallery.html) é o recurso
padrão para descobrir como fazer um determinado gráfico. Clique no gráfico que
quer fazer para ver o código que o gerou.


## Tarefa

Utilize o link enviado para a [lista de
emails](https://github.com/mat-esp/about#informa%C3%A7%C3%B5es) para criar um
repositório para seu grupo ou se juntar a um grupo já criado.
Anote o link para o repositório criado para seu grupo. Vocês precisarão desse
link.

Clone o repositório do seu grupo para seu computador. Não se esqueça de
configurar o git para um dos membros do grupo (`git config --global user.name
"Fulado de Tal"` e `git config --global user.email fulado@gmail.com`).

Nessa prática vamos utilizar dados da temperatura média mensal do Brasil com o
passar do tempo. Esses dados estão no arquivo `dados/brazil-TAVG-Trend.txt`
desse repositório e foram baixados do site
[Berkeley Earth](http://berkeleyearth.org/):
http://berkeleyearth.lbl.gov/regions/brazil

**IMPORTANTE**: tenha em mente o [checklist de
correção](https://github.com/mat-esp/about/blob/master/ISSUE_TEMPLATE.md#checklist-de-avalia%C3%A7%C3%A3o-do-professor)
quando fizer a tarefa. Não perca pontos de bobeira.
O site [pep8.org](http://pep8.org/) é uma boa referência para como escrever
código Python bem formatado.

Siga as instruções abaixo. Não se esqueça de fazer os commits. De preferência,
alterne a pessoa que está fazendo os commits.

1. Adicione no repositório um arquivo `alunos.txt` com os nomes completos de
   cada membro do grupo e seus nomes de usuário no github.com
2. Crie um Jupyter notebook chamado `python1.ipynb`. Todos os passos abaixo
   devem ser feitos nesse notebook. Use as células de texto do notebook para
   descrever o que você quis fazer com cada bloco de código.
3. Utilize o numpy para ler os dados do arquivo `dados/brazil-TAVG-Trend.txt`.
4. Calcule a temperatura média e o desvio padrão da temperatura do Brasil ao
   longo de todos os anos.
5. Faça um gráfico da anomalia de temperatura média mensal (eixo y) pelo tempo
   (eixo x). Coloque nomes nos eixos e um título para o gráfico. Outros
   enfeites ficam a seu critério. O resultado deve ficar parecido ao que está
   no site:

[![Figura do site.](http://berkeleyearth.lbl.gov/auto/Regional/TAVG/Figures/brazil-TAVG-Trend.png)](http://berkeleyearth.lbl.gov/regions/brazil)

**BÔNUS**: Adicione no seu gráfico a média anual e o intervalo de +- duas
incertezas (95% uncertainty range) como na figura do site. (Veja na galeria do
matplotlib como fazer isso.)


## Entrega das soluções

A solução de cada prática será um repositório no [Github](http://github.com/)
com o código feito pelos alunos.

A entrega das soluções será feita criando uma
[Issue](https://guides.github.com/features/issues/)
no repositório da disciplina
[mat-esp/about](https://github.com/mat-esp/about).
Utilize o link abaixo para ir direto para as Issues:

https://github.com/mat-esp/about/issues

Cada grupo deve criar uma Issue para entregar cada prática.
A issue deverá seguir o padrão abaixo:

* Título: Deve conter o nome da prática seguido dos nomes dos integrantes do
  grupo e a qual turma pertencem (caso haja mais de uma). Ex: "Prática
  Integração: Bilbo, John, Arthur - Turma 1"
* Corpo: Deve conter o link para o repositório do grupo (ex:
  `https://github.com/mat-esp-2016/integracao-sociedade-42`) e qualquer
  comentário que achar necessário (ex: problemas com os commits, erros que foram
  arrumados depois, dificuldades, etc).


## License

All content can be freely used and adapted under the terms of the
[Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)
