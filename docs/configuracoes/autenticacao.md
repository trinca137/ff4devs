# Autenticação e Autorização


!!! Sobre

    Para começar a utilizar nossos recursos, você deve possuir uma Chave de Acesso, previamente fornecida pela Fairfax.


Para obter autorização no consumo dos recursos da API, você deve enviar a Chave de Acesso no Header da requisição toda vez que fizer chamadas para a API.

A chave de acesso deve ser enviada como valor da propriedade: **Ocp-Apim-Subscription-Key**


```curl
curl -H 'Ocp-Apim-Subscription-Key: {Chave de Acesso}' \
```


