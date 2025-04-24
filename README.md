## Projeto fraud detection

### Problem:
Credit card fraud causes significant financial losses for consumers, merchants, and financial institutions. In addition to monetary losses, victims can suffer emotional distress and have their financial reputation damaged. For merchants, fraud can result in chargebacks, loss of merchandise, and damage to the company's image.

A fraude no cartão de crédito causa prejuízos financeiros significativos para consumidores, comerciantes e instituições financeiras. Além das perdas monetárias, as vítimas podem sofrer transtornos emocionais e ter sua reputação financeira prejudicada. Para os comerciantes, a fraude pode resultar em chargebacks (cancelamento da venda), perda de mercadorias e danos à imagem da empresa.

### Motivation:
The need to prevent credit card fraud lies in the protection of financial assets, the safety and well-being of individuals, and the integrity and sustainability of commerce and the financial system. Fraud prevention benefits everyone involved by creating a safer and more reliable environment for financial transactions.

A necessidade de impedir a fraude em cartões de crédito reside na proteção dos ativos financeiros, na segurança e bem-estar dos indivíduos e na integridade e sustentabilidade do comércio e do sistema financeiro. A prevenção da fraude beneficia a todos os envolvidos, criando um ambiente mais seguro e confiável para as transações financeiras.

### Solution:
The solution to credit card fraud involves a multifaceted approach that encompasses security technologies, prevention practices, and response measures on the part of consumers, financial institutions, and merchants.
Here we present a solution based on training an artificial intelligence classification model that can prevent fraud at the time of purchase, preventing the fraudster from achieving his goals by preventing the purchase from being made.

A solução contra a fraude no cartão de crédito envolve uma abordagem multifacetada que engloba tecnologias de segurança, práticas de prevenção e medidas de resposta tanto por parte dos consumidores quanto das instituições financeiras e comerciantes.
Aqui apresentamos uma solução pautada no treinamento de um modelo de classificação de inteligência artificial que poderá evitar a fraude na hora da compra, impedindo que o fraudador possa consumar seus objetivos não permitindo que a compra seja feita.

### Objective:
- The objective of this work is to train a classification model that can detect fraud in credit card payments, seeking to provide information, in real time, so that the purchase is not made if a high probability of fraud has been detected.

- O objetivo desse trabalho é treinar um modelo de classificação que possa detectar fraudes no pagamento com cartão de crédito buscando fornecer informações, em tempo real, para que a compra não seja realizada caso tenha detectado alta probabilidade de ser fraude.

### Data Origin:
- Dataset: https://raw.githubusercontent.com/amankharwal/Website-data/master/payment_fraud.csv

- The dataset used is online shopping transaction data collected from an e-commerce retailer. The dataset contains over 39,000 transactions, each containing 5 features that will describe the nature of the transactions.

- O conjunto de dados utilizados são dados de transações de compras online coletados de um varejista de comércio eletrônico. O conjunto de dados contém mais de 39.000 transações, cada uma contendo 5 características que descreverão a natureza das transações.

- Aqui está o que as colunas representam:

accountAgeDays = idade da conta em dias
numItems = nro de items da compra
localTime = hora local
paymentMethod = cartão utilizado no pagamento
paymentMethodAgeDays = tempo em dias que a fatura ficou em aberto até o pagamento
label = indica se houve fraude (1) ou não (0)