
# Analise de sentimentos com o Language Studio no Azure AI

Neste Artigo, vou mostrar um pouco de como foi usar o Azure AI Language Studio para fazer analise de sentimentos de acordo com analise de sentenças de um um texto. Espero que descrever esse processo tambem te ajude a utilizar esse recurso incrivel.

# Criando recurso de linguagem no Portal Azure
para começar, no [Portal Azure](https://portal.azure.com/), é necessario criar um recurso de linguagem. Para isso, clique em criar um novo recurso, em seguida no menu IA + Machine Learning, selecione a opção **Análise de texto**, e clique em criar, e na tela seguinte em **continue to create your resource**(não é necessario configurar algo nessa tela).

![](https://github.com/henriquesoaresjr/Analise-de-sentimentos-com-LanguageStudio-AzureAI/blob/main/prints%20auxiliares/criando%20recurso%20de%20linguagem.png)
![](https://github.com/henriquesoaresjr/Analise-de-sentimentos-com-LanguageStudio-AzureAI/blob/main/prints%20auxiliares/analise%20de%20texto.png)
![](https://github.com/henriquesoaresjr/Analise-de-sentimentos-com-LanguageStudio-AzureAI/blob/main/prints%20auxiliares/criando%20o%20recurso.png)

Após isso, configure essas tela selecionando o grupo de recurso(caso não tenha pode criar um na mesma tela logo abaixo conforme imagem abaixo), e de tambem um nome ao recurso, e selecione o tipo de preço **Free F0**.

![](https://github.com/henriquesoaresjr/Analise-de-sentimentos-com-LanguageStudio-AzureAI/blob/main/prints%20auxiliares/preenchendo%20detalhes1.png)

Após isso, marque a caixa de analise e confirmação dos termos no Aviso de uso responsavel da IA, e clique em examinar + criar. Feito isso, na tela seguinte que se abrir basta clicar em criar, e aguardar seu recurso de linguagem ser criado.

![](https://github.com/henriquesoaresjr/Analise-de-sentimentos-com-LanguageStudio-AzureAI/blob/main/prints%20auxiliares/criando.png)

# Usando o Language Studio
Ao fazer o login no Language Studio pela primeira vez, voce vai precisar a assinatura do Azure que voce possui, e tambem o recurso, que no caso é o que foi criado anteriormente.

![](https://github.com/henriquesoaresjr/Analise-de-sentimentos-com-LanguageStudio-AzureAI/blob/main/prints%20auxiliares/infos.png)

# Usando o recurso de analise de sentimentos e opiniões
Após logado no Language Studio, para usar o recurso de analise de sentimentos, voce deve ir no menu **Classify text**, e em seguida mais abaixo selecionar o recurso **Analyze sentiment and mine opinions**.
![](https://github.com/henriquesoaresjr/Analise-de-sentimentos-com-LanguageStudio-AzureAI/blob/main/prints%20auxiliares/analise%20de%20sentimentos.png)

Para testar o recurso, voce pode digitar o próprio texto, usar textos de exemplo ou até mesmo fazer upload de arquivos da sua galeria. Voce seleciona a linguagem do texto que esta sendo inserido, marca a opção mais abaixo de que esta ciente que a demo pode estar gerando custos (caso seu periodo de teste ou 200 dolares de credito tenham acabado), e clica no botão Run.
![](https://github.com/henriquesoaresjr/Analise-de-sentimentos-com-LanguageStudio-AzureAI/blob/main/prints%20auxiliares/tela%20do%20recurso%20de%20analise%20de%20sentimentos%20de%20texto.png)

Deixo abaixo alguns exemplos de testes que fiz.

![](https://github.com/henriquesoaresjr/Analise-de-sentimentos-com-LanguageStudio-AzureAI/blob/main/prints%20auxiliares/resultado%20analise%20de%20sentimento%20texto1.png)
![](https://github.com/henriquesoaresjr/Analise-de-sentimentos-com-LanguageStudio-AzureAI/blob/main/prints%20auxiliares/texto2.png)
![](https://github.com/henriquesoaresjr/Analise-de-sentimentos-com-LanguageStudio-AzureAI/blob/main/prints%20auxiliares/analise%20de%20sentimento%20do%20documento%20texto2.png)
![](https://github.com/henriquesoaresjr/Analise-de-sentimentos-com-LanguageStudio-AzureAI/blob/main/prints%20auxiliares/analise%20das%20senten%C3%A7as%20do%20texto2.png)

# Conclusão
Essa atividade foi incrivel de realizar, pois é muito curioso quando voce começa a estudar algo e não tem a noção da dimensão que isso é capaz de suprir. Nesse exemplo de atividade de reconhecer sentimentos em texto, é algo que até então eu desconhecia na area de IA, e achei incrivel que o Language Studio não só detecta emoções no texto todo, como analisa emoções em cada sentença que ele encontra no texto. Foi uma atividade na qual aprendi muito, e vou buscar mais conhecimento sobre o assunto.

# Excluindo grupo de recurso
Pode parecer algo sem importancia, mas é recomendado que após não utilizar mais os recursos, voce excluir o grupo de recursos, para que o mesmo não consuma créditos da sua conta ou até mesmo gere gastos, caso voce não esteja mais no período gratuito de testes e ja tenha usado os 200 dólares concedidos ao criar uma conta nova. Então deixei aqui tambem um resumo de como excluir um grupo de recursos.
Para isso, no [Portal Azure](https://portal.azure.com/), selecione o grupo de recursos que voce criou, e em seguida marque-o e clique em Excluir o grupo de recursos.

![](https://github.com/henriquesoaresjr/Analise-de-sentimentos-com-LanguageStudio-AzureAI/blob/main/prints%20auxiliares/excluindo%20grupo%20de%20recursos.png)








