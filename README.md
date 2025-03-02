# ServerRestAPI
Teste de APi Rest CI CD
Criação de testes de API utilizando POSTMAN,NEWMAN e NEWMAN-HTML-EXTRA

  ## o que é
  Este repositório foi criado no bootCamp de teste de API rest.
 ## Tecnolgia utilizada
 Postman
 node version v1.16.1
 newman 6.2.1
 newman-reporter-html
  ## Documentações
  - Análise técnica: 
  -  Doc da API: [Consulte Swagger](https://serverest.dev/#/) 
  ##Como instalar o ambiente
  - Primeiro instale o node em seu computador [baixe aqui](https://nodejs.org/en/download)
  -  Segundo: realiza a instalação do newman de maneira global [baixe aqui a dependência](https://www.npmjs.com/package/newman#using-newman-cli)

    npm install -g newman
    
  -  Terceiro: realize a instalação da dependência dos relatórios (opcional) [newman-reporter-html](https://www.npmjs.com/package/newman-reporter-htmlextra)
    
    npm i newman-reporter-html
    
  ## Como rodar os testes
  ### Pelo postman web ou desktop
  - Import a collection e o environment
  - Execute os teste de forma manual ou automatizada
  ### Pelo newman
  - Abra o console de preferência
  - Execute a seguinte linha de comando pra rodar o teste:
    ```
    `newman run ServerRest.postman_collection.json -e serverRest_env.postman_environment.json -r cli
    ```
    - Execute os teste com relatório:
     ```
      newman run ServerRest.postman_collection.json -e serverRest_env.postman_environment.json -r cli,htmlextra
     ```

      ### Report
      Se você optou por rodar os testes com o report htmlexxtra, você gerou um arquivo html com o resultado dos testes e para verificar as validações você pode abrir a pasta **newman** que foi criada no local em que os arquivos de collection e environment se encontram.
  

  ## Entre em contato
 
