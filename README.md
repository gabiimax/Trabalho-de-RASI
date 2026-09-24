# Trabalho-de-RASI
### Resumo

Neste trabalho, foi desenvolvido um ambiente para execução e gerenciamento de uma aplicação web utilizando uma máquina virtual, Docker e Python com Flask. Inicialmente, foi preparada uma máquina virtual utilizando Ubuntu Server ou Lubuntu, realizando as configurações necessárias para permitir o acesso à internet e a comunicação com a máquina hospedeira. Também foi configurado o acesso remoto por meio do SSH, permitindo que os comandos e demais configurações fossem realizados diretamente pelo terminal da máquina hospedeira.

Após a preparação da máquina virtual, foram realizados os primeiros procedimentos com o Docker. O sistema foi atualizado e a instalação do Docker foi verificada por meio de comandos no terminal. Também foi executado o container de teste `hello-world`, com o objetivo de confirmar que o Docker estava funcionando corretamente no ambiente configurado.

Em seguida, foi criada uma aplicação web utilizando Python e o framework Flask. Para organizar o projeto, foram criados os arquivos necessários para a aplicação e suas dependências. A aplicação foi então preparada para ser executada dentro de um container Docker. Para isso, foi criado um `Dockerfile` utilizando obrigatoriamente a imagem base `python:3.14-slim`, além do arquivo `requirements.txt` contendo o Flask. Depois disso, foi realizado o processo de construção da imagem com o comando `docker build` e a execução do container com o mapeamento da porta 5000.

Após colocar a aplicação em funcionamento, foram realizados testes pelo navegador utilizando o endereço IP da máquina virtual e a porta configurada. Também foram utilizados os comandos `docker ps` e `docker logs` para verificar o funcionamento e acompanhar as informações do container.

Como parte da expansão da aplicação, foram adicionadas novas rotas ao projeto, como `/sobre` e `/contato`. Cada página recebeu conteúdos, títulos e elementos visuais próprios, utilizando recursos básicos de HTML e CSS, como títulos, parágrafos, cores e fontes. Depois das alterações, a imagem Docker foi reconstruída e o container foi reiniciado para que as modificações fossem aplicadas e testadas.

Por fim, o trabalho também envolveu a utilização do GitHub para documentar os primeiros passos realizados por cada integrante do grupo. Dessa forma, a atividade permitiu colocar em prática conceitos de máquinas virtuais, acesso remoto por SSH, containers, Docker, Python, Flask e GitHub, demonstrando como uma aplicação web pode ser criada, modificada e executada em um ambiente isolado e reproduzível.
