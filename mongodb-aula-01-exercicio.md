  GNU nano 2.4.2                              Arquivo: mongodb-aula-01-exercicio.md                                                                    

# MongoDB - Aula 01 - Exercício
        auto: Wesley Serafim de Araújo
## Importando os restaurantes

        connected to: 127.0.0.1
        2015-11-09T22:27:28.823-0200 check 9 25359
        2015-11-09T22:27:28.828-0200 imported 25359 objects


## Contando os restaurantes

        wsaultra(mongod-2.6.10) be-mean> db.restaurantes.find({}).count()
        25359
