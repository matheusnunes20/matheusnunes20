Fala Dev's 

Meu nome é Mateus Nunes e sou analista de sistema/desenvolvedor, estou fazendo especialização em Egenharia de Software com DevOps e vim hoje aqui compartilhar com vocês um problema que eu tive para fazer meu projeto da prova final da cadeira que estou matriculado.
A cadeira é seguração da informação e a prova final dela é para realizar testes em algum código para saber quais são suas vunerabilidade e até mesmo o que melhorar no código com isso eu decidir utilizar uma ferramente que eu acredito não seja tão conhecida que é o SonarqQube aonde ele lhe ajudar a analisar o código e lhe mostra pontos de vunerabiliadade do seu código e mostra também o que pode ser melhorado.

Meu problema foi com suas configuração e inicialização da ferramenta, pois muitos tutorias estavam incompletos e tinha varios momentos que eu ficava com muitas dúvidas e por conta disso eu decidir fazer uma documentação que possa ajudar o próximo dev que for utilizar essa ferramente que eu achei sensacional.

*INTRODUÇÃO*

Essa documentação está sendo desenvolvida para auxiliar os novos usuários do SonarQube, pois foi notado que grande parte dos tutorias (vídeos ou passo a passo)  e documentações tem falta de alguma informação que atrapalha a evolução do leitor para conseguir instalar e configurar o SonarQube onde eu também passei por esse problema e por isso decidir criar essa documentação para auxiliar os usuários dessa ferramenta que é excelente para você descobrir os possíveis erros e vulnerabilidade do seu código.


CASO DE USO 

1.	Fluxo
   
1.1.	Verifique se na sua máquina possui um JDK (Java Development Kit) mais atualizado disponível no site da Oracle (https://www.oracle.com/br/java/technologies/downloads/) 

1.1.1.	Caso você não souber fazer instalação do seu JDK vou está deixando link de um tutorial que vai lhe auxiliar nessa parte (https://medium.com/beelabacademy/configurando-vari%C3%A1veis-de-ambiente-java-home-e-maven-home-no-windows-e-unix-d9461f783c26)

1.1.2.	Após você fazer verificação da versão do seu JDK (Java Development Kit) vamos agora fazer o download do SonarQube no seu site oficial

1.1.2.1.	Bastante importante informar que seu JDK deve ser uma versão superior a versão do SonarQube (exemplo: Se o seu sonar foi versão 9 o seu JDK precisa ser 11 ou superior)

1.1.2.2.	Agora vamos baixar o SonarQube no site oficial da ferramenta (https://www.sonarsource.com/products/sonarqube/downloads/?gads_campaign=SQ-Mroi-PMax&gads_ad_group=Global&gads_keyword=&gad_source=1&gclid=Cj0KCQiAgK2qBhCHARIsAGACuzlIhdIbl7suqMUPcl1L13B4cRcM6m9OuQsTKoa2YBzU04zcw1mB0nMaAqhyEALw_wcB)

1.1.2.3.	No site você escolhe a opção de sua preferência, mas vou está utilizado à edição da comunidade que o download é gratuito.

1.1.2.4.	Ao clicar no download você vai armazenar essa pasta do Sonar na raiz do seu computador (disco C:) ficará mais fácil de localizar o arquivo na máquina.

1.1.2.5.	Agora chegou à hora de configurar/inicializar o Sonar 

1.1.2.5.1.	Abra o promp de comando ou Power Shell, escolha de sua preferência, dica importante que eu dou é abrir como administrador, pois dessa forma evita algum tipo de erro possa dar com relação à segurança

1.1.2.6.	Ao abrir o prompt vá até onde está armazenada a pasta do Sonar e entre na pasta Bin

1.1.2.7.	Ao chegar nessa parte selecione a pasta que está relacionada com o sistema operacional da sua máquina e entre nela

1.1.2.8.	Vamos agora lançar o comando de inicialização no prompt; digite o seguinte comando no terminal StartSonar.bat 

1.1.2.9.	Com esse comando ele irá inicializar o Sonar na sua maquina com isso você abre o seu navegador de sua preferência e usa a porta padrão do sonar 9000 (localhost:9000) esse é link para acessar o Sonar na web.

1.1.2.10.	Ao abrir o link do sonar ele vai pedir um usuário e senha que é padrão do Sonar que são usuário admin e senha admin.

1.1.2.11.	Um ponto importante!  Eu só conseguir fazer rodar o Sonar com versão 17.0.9 do JDK e 9.9.2.77730 do SonarQuber.

Espero ter ajudado você ai que está mexendo pela primeira vez no SonarQube e estava com problemas para configura-ló; com tempo se eu ver que tem como melhorar essa documentação vou atualizar ela aos poucos e qualquer dúvida pode mandar que eu vou está respondendo você dev.

