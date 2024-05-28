<h1>Projeto de Análise de Dados - Matérias Primas na Agricultura</h1><br>

![Banner site frete grátis minimalista branco e cinza](https://github.com/lucasvieirazx/agricultura_data_analysis/assets/140829235/cc8a20b1-85e5-4c12-8f01-65c46a120cdd)

Este projeto consiste em uma análise de dados das matérias primas na agricultura. Para tal, foi utlizado Excel para criar a planilha com os dados e Python para fazer a análise e vizualização dos números disponíveis. Nos arquivos, você também pode conferir uma apresentação com os principais insights levantados durante e análise.

<h2>Conjuntos de dados</h2>
Os dados utilizados estão distribuidos em uma tabela, com informações sobre os materiais, quantidade vendida, e valor dos produtos, variação do preço entre outros dados. 

<h2>Apresentação</h2>
A análise é apresentada em um documento PDF.

<h2>Apresentação do PDF:</h2>
Esta apresentação oferece insights aprofundados sobre diversos aspectos da análise, como preço médio da venda dos produtos.

<h2>Ferramentas</h2>
Para a execução da análise, foram utilizadas algumas ferramentas, tais quais:
<ul>
 <li>Excel: Local dos dados</li>
 <li>Python: Para realizar a análise utilizando o Jupyter Notebook. O passo a passo está no arquivo <i>analise.ipynb</i></li>
 <li>Canva: Confecção da apresetnação final com panorama geral dos dados.</li>
</ul>

<h2>Perguntas de Negócio</h2>
<h4>Q1: Descubra a variação normal do preço de cada matéria-prima:</h4>
Podemos observar que a maioria das matérias-primas tem % de mudança frequente ideal inferior a 5%.
<h4>Q2: Encontre a matéria-prima que tem o menor preço ao longo dos anos:</h4>
Podemos ver que o algodão e a borracha são de preços mais baixos,
vamos comparar preços para entender melhor qual é o mais baixo. Algodão é matéria-prima de menor preço nos últimos anos, tanto o algodão quanto a borracha são materiais de baixo preço. A partir dos gráficos pudemos analisar as matérias-primas em tipos de acordo com seu preço ao longo dos anos.<br>
Materiais de baixo preço:
<ul>
 <li>algodão, couro, softlog, log duro, preço de madeira serrada macia, borracha.</li>
</ul>
Materiais de alto preço:
<ul>
 <li>lã grossa,copra,lã fina,madeira serrada dura,pasta de madeira,madeira compensada.</li>
</ul>
<h4>Q3: qual matéria-prima tem a maior e menor variação de % de preço:</h4>
Podemos ver a maior % de mudança em mais de 60 para madeira serrada macia e a menor % de mudança é para madeira compensada em menos de 20.
<h4>Q4: Encontre as matérias-primas com mudança drástica de preço:</h4>
A mudança de preço é drástica para o preço de tora dura entre materiais de baixa faixa de preço e entre materiais de alto preço, são os preços de lã fina.
<h4>Q5: Descobrir a faixa de preço de matérias-primas de baixo preço:</h4>
Inclui: O intervalo interquartil está entre Q3 e Q1 mínimo, primeiro quartil (Q1), mediana, terceiro quartil (Q3) e máximo e outliers.

<h2>Inferências e Conclusão</h2>
<ul>
 <li>Conluise que é possivel descobrir as matérias-primas de alta e baixa gama de acordo com seus preços.</li>
 <li>Alta e baixa % de variação dos materiais.</li>
 <li>Pudemos identificar a variação de preços ao longo dos anos.</li>
 <li>Correlação entre eles usando um mapa de calor.</li>
</ul>

<h2>Trabalho futuro</h2>
Além disso, poderíamos descobrir a relação entre as matérias-primas em detalhes e, com a ajuda do conhecimento do negócio, poderíamos descobrir as matérias-primas mais próximas. Também pudemos prever os preços das matérias-primas analisando os anos anteriores. Prevendo a variação de preços e com base nisso, poderíamos planejar nosso uso de matéria-prima com antecedência para o próximo ano e descobrir quaisquer materiais alternativos.
