Olá Analistas, desenvolvedores e recrutadores. Este readme irá apresentar a collection para testes automatizados de APIREST utilizando postman.

* URL base para testes deste projeto:
  - swagger grafana K6: https://test-api.k6.io/

### Setup necessário ###


* Ter o Postman instalado na sua máquina

  ```
  https://www.postman.com/downloads/
  ```

 ### Importar collection forma 1 ###

  ```
  - Clique no arquivo testes-api-rest-postman-collection.json
  - Clique no botão Raw
  - Copie a URL do seu navegador que está exibindo o arquivo
  - Abra o Postman
  - Selecione o menu File -> Import
  - Clique na aba Link
  - Cole o conteúdo copiado o campo Enter a URL
  - Clique no botão Continue
  - Clique no botão Import
  ```

 ### Importar collection forma 2 ###

  ```
  - Efetue o download deste repositório ou do arquivo test-api automation.postman_collection.json
  - Abra o Postman
  - Selecione o menu File -> Import
  - Selecione a aba File
  - Clique no botão Upload Files
  - Navegue até o diretório onde você salvou o arquivo e selecione-o
  - Clique no botão Import
  ```  

 ### Executar os testes forma 1

  ```
  - Clique na aba runner localizado no rodapé do postman
  - Arraste a collection em run order
  - Selecione opcao "run manually"
  - Clicar em run test-api-automation
  ```    

 ### Executar os testes forma 2 (criando CICD schedule)

  ```
  - Clique na aba runner localizado no rodapé do postman
  - Arraste a collection em run order
  - Selecione opcao "schedule runs"
  - Definir o nome "CICD" no campo schedule name
  - Clicar em schedule run
  ```     

### Repositório github ###

* Consulte meu repositório de diversos projetos no github através da url

```
https://github.com/israfaioli?tab=repositories
```