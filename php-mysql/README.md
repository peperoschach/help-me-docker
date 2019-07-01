### Especificações
  
- PHP 7.2  
- Apache  
- Mysql 5.7  

### Rodando os containers

1. Certifique-se que você tenha o docker instalado em sua máquina.
2. Certifique-se que os arquivos __Dockerfile__ e __docker-compose.yml__ estão na raiz do seu projeto.
3. Crie um diretório __www/__.
4. Dentro do diretório __www/__ crie um arquivo __index.php__ com o seguinte conteudo: 
    ```
    <?php
      phpinfo();
    ?>
    ```
5. No terminal vá até o diretório do seu projeto, execute o comando `docker-compose up -d`.
6. Em um navegador digite __http://localhost__
7. Se tudo ocorreu bem deverá aparecer em seu navegador as informações sobre a versão do php.