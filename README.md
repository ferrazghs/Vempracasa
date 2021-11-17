<html>
<body>
  
 <h1 align="center"> API 4º Semestre Banco de Dados</h1>
  
  <p align="center">
 <a href="#-resumo-do-projeto-clipboard"> Descrição do Projeto</a> •
 <a href="#-tecnologias-adotadas-computer">Tecnologias Adotadas</a> •
 <a href="#-contribuições-individuais-dart">Contribuições Individuais</a> •
 <a href="#-aprendizados-efetivos-book">Aprendizados Efetivos</a>
</p>
  
  ---
  
  <h2> Autor :necktie: </h2>
  <table align="center">
   <tr>
    <td align="center"><a href="https://www.linkedin.com/in/gabrielferraz01/">" alt=""/><br/><b>Gabriel Ferraz</b></a>
      <br/>
       Developer
     </td>
   </tr>
  </table>

 ---
  
  <h2 style="font-family:roboto;"> Descrição do Projeto :clipboard:</h2>
  
  <p align="justify" style="font-family:roboto;"> :calendar: <b>#VEMPRACASA</b> é uma parceria entre a <a href="https://www.oracle.com/br/index.html">Oracle</a> e a FATEC São José dos campos, a proposta apresentada pela a empresa parceira tem a finalidade no desenvolvimento de um sistema que realiza agendamentos de eventos nos espaços da Casa Oracle, o sistema tem o intuito de solucionar um problema recorrente que a empresa possuía no agendamento manual dos eventos..</p>
  
  <p align="justify" style="font-family:roboto;"> O sistema tem diversas funcionalidades que tornam o agendamento de eventos algo intuitivo e prático para o usuário final, foi inteiramente desenvolvido utilizando a metodologia ágil Scrum. No aplicativo temos três tipos de usuários que consistem em: Organizador, Administrador, Convidado.</p>

  <p align="justify" style="font-family:roboto;"> Cada usuário tem o seu papel definido dentro do programa, o organizador tem como principal funcionalidade a solicitação de um evento, onde é possível cadastrar um titulo, data/hora de inicio e fim do encontro, uma breve descrição, imagem de divulgação do evento, caso o evento necessite de fornecedores terceirizados é possível verifica a lista dos fornecedores já cadastrado no sistema, aquele que melhor se encaixa, definir também se o evento é aberto para todos os usuários (publico) ou apenas para funcionários Oracle (privado), e por fim adicionar os convidados através do e-mail correspondente.</p>
  
  <p align="justify" style="font-family:roboto;"> Após a solicitação do evento por parte do organizador, o encontro deve passar pela a aprovação do administrador geral do programa, onde o usuário “admin” tem a possibilidade de visualizar informações dos eventos que foram solicitados e definir se será aprovado ou não, para deixar a ação de aprovar mais intuitiva foi desenvolvida uma priorização na solicitação de eventos, assim usuários que possuem uma função maior na hierarquia da empresa tem uma prioridade na aprovação. O “admin” também tem a possibilidade de cadastrar novos fornecedores dentro do sistema, que serão utilizados durante os eventos. Depois de aprovado o evento, os convidados cadastrados recebem um e-mail com informações sobre o evento, e o organizador a confirmação que sua solicitação foi aprovada.</p>
  
  <p align="justify" style="font-family:roboto;"> Os convidados são divididos em externos e internos. Para se cadastrar no programa esses usuários devem acessar a aba especifica e definir se são funcionários Oracle ou não. Funcionários Oracle além de participar e receber via e-mail os eventos, tem o poder de solicitar para o “admin” para que se tornem organizadores. Convidados externos apenas participam dos eventos.</p>
  
  
   <p align="justify" style="font-family:roboto;"> O projeto por fim trás uma facilidade muito grande para seus usuários, além da solicitação rápida e intuitiva de um evento, é possível ter uma segurança através da sua aprovação por meio do administrador, além disso, a confirmação do evento via e-mail para os convidados trás uma grande facilidade na comunicação.</p>

 ...
  
  <h2 style="font-family:roboto;"> Tecnologias Adotadas :computer:</h2>
   
  * [Java](https://www.java.com/pt_BR/)
<p align="justify" style="font-family:roboto;"> O Java é uma linguagem de programação orientada a objetos. Foi utilizada durante o desenvolvimento do back-end do projeto. Por conta dos integrantes do grupo já possuírem um conhecimento prévio no desenvolvimento baseado nessa linguagem, ela é muita utilizada no mercado de trabalho, além de possuir uma extensa documentação, facilitando o desenvolvimento do projeto.</p>
  * [Spring Boot](https://spring.io/)
  <p align="justify" style="font-family:roboto;">Spring boot é um framework Java open-source que facilita o desenvolvimento de aplicações baseadas em Java, tornando o desenvolvimento mais rápido e dinâmico. Além de possuir diversas funcionalidades, o recurso foi utilizado durante o projeto para fazer a configuração de todas as bibliotecas que foram utilizadas, tornando o desenvolvimento mais rápido, além de um código fonte mais limpo. O framework foi escolhido pois ele facilita durante o desenvolvimento de projetos, fazendo com que os programadores se preocupem apenas com a implementação das regras de negocio.</p>
  * [JavaScript](https://www.javascript.com/)
  <p align="justify" style="font-family:roboto;">Javascript é uma linguagem de programação de script em alto nível, utilizado em páginas web. Foi utilizada durante o projeto para implementar no software a interação que o usuário possui com nossas páginas web, tornando assim sua navegação mais dinâmica.  A linguagem foi escolhida pelo grupo, pois é uma das linguagens mais utilizadas no mercado de trabalho para esse tipo de interação, além da alta compatibilidade com navegadores web.</p>
  * [Angular](https://angular.io/)
    <p align="justify" style="font-family:roboto;"> Angular é uma plataforma de aplicações web de código-fonte aberto e front-end baseado em typescript, essa plataforma é utilizada na construção otimizada de interfaces de aplicações, utilizado HTML, CSS e principalmente Javascript. Foi usada durante o desenvolvimento das páginas web presente no projeto, possibilitando uma programação mais ágil e fácil. Além de ser uma plataforma bastante utilizada, é open-source ou seja, existe uma grande variedade de conteúdos e funcionalidades disponibilizadas dentro da plataforma.</p>
  * [Oracle](https://www.oracle.com/tools/downloads/sqldev-downloads.html)
      <p align="justify" style="font-family:roboto;"> Oracle é um Sistema Gerenciador de Banco de Dados de alto nível que utiliza banco de dados relacional. O SGBD foi utilizado durante a execução dos scipts SQL para a prototipação das tabelas e colunas de acordo com o modelo relacional desenvolvido previamente, além da manutenção e armazenamento dos dados do sistema. Foi escolhido pela equipe, pois é um SGBD robusto e com uma grande variedade de funcionalidades. </p>
  * [Figma](https://www.figma.com/)
    <p align="justify" style="font-family:roboto;"> Figma é um editor gráfico de vetor e prototipagem de projetos. Ele foi utilizado no projeto durante a prototipação do “Product Backlog Building” um método apresentado pelo PO da equipe, que foi utilizado para criação de um backlog colaborativo e de forma organizada, para que cada um dos integrantes do time pudesse expor suas ideias referentes ao projeto e assim organizar nossas funcionalidades, além disso, a ferramenta foi usada para a criação dos “Wireframes” do projeto, que posteriormente foram apresentadas ao clientes e validadas, a ferramenta foi escolhida pela equipe, pela a alta utilização no mercado e fácil utilização do software.</p>
  * [Jira](https://vempracasa.atlassian.net/) 
     <p align="justify" style="font-family:roboto;">Jira é uma ferramenta que permite o monitoramento de tarefas e acompanhamento de projetos em um único lugar. Utilizamos esse software para desenvolver e monitorar nosso Sprint backlog, onde podemos repartir as funções a serem desenvolvidas em “cartões” para um melhor acompanhamento de evolução e organização e atribuir quem é o responsável por aquela tarefa a ser desenvolvida, além de separar por área (back-end, front-end ou banco de dados) e delegar ao responsável uma data de inicio e fim daquela tarefa. O software foi escolhido pela equipe pois é utilizado em grande escala no mercado de trabalho, além de ser uma ferramenta fácil e intuitiva.</p>

  
  ---
  
  <h2 style="font-family:roboto;"> Contribuições Individuais :dart:</h2>
  
  <h3>Modelo Conceitual do banco de dados</h3>
  <p align="justify" style="font-family:roboto;">A modelagem de dados conceitual é uma descrição do projeto de banco de dados de forma independente de implementação em um SGBD, é um modelo que possui um alto nível de abstração, é o primeiro passo feito antes da implementação final dentro do SGBD Oracle. O MER (Modelo Entidade Relacionamento) é composto por : Entidade (representação de um conceito físico), Atributo (propriedades especificas de uma entidade) e Relacionamento (associações entre uma ou mais entidades</p>
  
  <p align="justify" style="font-family:roboto;">O modelo foi desenvolvido utilizando o software “brModelo” especifico para a criação do MER. Após a definição do “Product Backlog” e o desenvolvimento das perguntas que foram enviadas a empresa parceira através do PO do time, para obter uma visão mais aprofundada sobre o projeto, foi feito uma análise sobre a proposta e com isso foi possível o desenvolvimento das entidades, atributos e relacionamentos presentes no modelo. Essa parte foi crucial no inicio do projeto para elaborar um modelo de dados consistente e funcional, com o MER conseguimos resolver questões importantes que refletiram durante as sprints, por exemplo, o relacionamento que os usuários do sistema têm com os eventos criados pelos mesmos.</p>
 
  <details>
  <summary>Demonstração do modelo conceitual</summary>
  <br>
   <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Vempracasa/blob/main/images/conceitual.jpg" width="1000px;" alt=""/>
  </details>
  
  <h3> Modelo relacional banco de dados</h3>
  <p align="justify" style="font-family:roboto;">O modelo relacional é um tipo de modelo lógico, é também uma parte importante durante o desenvolvimento de um banco de dados completo e funcional, esse modelo apresenta uma estrutura diferente do modelo conceitual, é baseado em : Linhas, Colunas e Chave primária(PK) s e se relacionam através de chaves estrangeiras(FK), é um modelo intermediário, está localizado entre o modelo conceitual que é o primeiro passo, e o a estruturação no SGBD. Para o desenvolvimento desse modelo foi utilizado à ferramenta “Vertabelo” que é possível estruturar seu modelo relacional utilizando todas as informações necessárias.</p>
  
  <p align="justify" style="font-family:roboto;">O desenvolvimento foi feito levando em consideração as entidades, atributos e relacionamento do conceitual, nesse novo modelo as entidades se tornam tabelas, os atributos se tornam colunas e os relacionamentos são feitos através de chaves estrangeiras, nele também ocorre a “trigramação” que é uma técnica utilizada para nomear tabelas e colunas.</p>
  
  <details>
  <summary>Demonstração modelo relacional</summary>
  <br>
   <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Vempracasa/blob/main/images/relacional.jpg" width="'1000px;" alt=""/>
  </details>
  
  <h3> Documentação de dados</h3>
  <p align="justify" style="font-family:roboto;">Após o desenvolvimento do modelo relacional pela ferramenta foi gerada uma documentação de dados através de um arquivo pdf, essa documentação foi entregue ao cliente, e descreve todas tabelas, colunas e relacionamento que o banco de dados possui, caso seja necessário algumas atualização na estrutura do código SQL o cliente consegue de forma fácil e rápida ter acesso a estrutura atual.</p>
  
   <h3>Estruturação do banco de dados </h3>
  <p align="justify" style="font-family:roboto;">Após a finalização dos modelos, foi feito a estruturação do banco de dados através do modelo relacional para linguagem SQL no banco de dados Oracle utilizando comando DML.</p>
  <p align="justify" style="font-family:roboto;">Os códigos SQL abaixo são alguns exemplos  de códigos SQL que foram desenvolvidos durante a estruturação do banco de dados.</p>
 
   <p align="justify" style="font-family:roboto;"><b>Comando DML para criar algumas tabelas no banco de dados, atribuindo suas colunas e especificando as restrições de integridade conforme o modelo relacional</b></p>
   
  <p align="justify" style="font-family:roboto;">
     <b>Linha 1 (comando DML para criação de tabela)</b>
       <br>
    CREATE TABLE Evento
       <br>
  <b>Linha 2 (atribuindo a coluna uma chave primaria e denominando um nome a sua constraint)</b>
       <br>
    evt_id Integer CONSTRAINT pk_evento PRIMARY KEY,
       <br>
  <b>Linha 3 (atribuindo a coluna uma restrição que não aceita valores nulos)</b>
       <br>
    evt_titulo Varchar2(30)  NOT NULL,
       <br>
    evt_descricao Varchar2(80),
       <br>
    evt_data_inicio Varchar2(100)NOT NULL,
       <br>
    evt_data_fim Varchar2(100) NOT NULL, 
       <br>
    evt_tipo Varchar2(10) NOT NULL,
       <br>
  <b>Linha 9 (imputando uma valor default NULL, caso não seja inserido nenhum valor na coluna)</b>
       <br>
    evt_status Integer DEFAULT NULL,
       <br>
    evt_imagem Varchar2(200),
       <br>
    usu_email Varchar2(80)
       <br>
) ;
</p>
                                                   
  <p align="justify" style="font-family:roboto;">
     <b>Linha 1 (comando DML para criação de tabela)</b>
       <br>
                                                
CREATE TABLE Usuario (
        <br>                                        
    usu_email Varchar2(80) CONSTRAINT pk_usuario PRIMARY KEY,
         <br>                                                                               
    usu_nome Varchar2(80) NOT NULL,
         <br>                                        
<b>Linha 3 (adicionando uma restrição de chave única á coluna, impossibilitando valores iguais em colunas diferentes)</b>
         <br>                                        
    usu_cpf Varchar2(15) CONSTRAINT uk_usuario_cpf UNIQUE NOT NULL,
         <br>                                        
    usu_telefone Varchar(50) NOT NULL,
         <br>                                                                      
    usu_departamento Varchar2(30),
         <br>                                        
    usu_nome_empresa Varchar2(50),
          <br>                                        
    usu_id_oracle Integer,
          <br>                                        
    usu_comprovante_vacinacao Varchar(200),
         <br>                                        
    usu_tipo Varchar2(20)NOT NULL,
        <br>                                        
    usu_cargo Varchar2(50),
         <br>                                        
    usu_senha Varchar2(100) CONSTRAINT uk_usuario_senha UNIQUE NOT NULL
          <br>                                        
) ;
</p>
     <p align="justify" style="font-family:roboto;"><b>Tabela de relacionamento (Usuário – Evento)</b></p>
    <p align="justify" style="font-family:roboto;">
                                                
CREATE TABLE Usuario_Evento (
      <br>
    evt_id Integer,
      <br>
    usu_email Varchar2(80),
      <br>
<b>Linha 3 (atribuição das chaves primárias da tabela, informando duas colunas, tornando assim uma chave primária composta)</b>
      <br>
    CONSTRAINT pk_usuario_evento PRIMARY KEY (evt_id,usu_email)
      <br>
) ;
  </p>
  <p align="justify" style="font-family:roboto;"><b>Especificação das chaves estrangeiras da tabela Usuario_Evento, referenciando as tabelas de origem.</b></p>
    <p align="justify" style="font-family:roboto;">
ALTER TABLE Usuario_Evento ADD CONSTRAINT fk_usuario_evento_evt_id
      <br>
    FOREIGN KEY (evt_id)
      <br>
    REFERENCES Evento (evt_id);
      <br>
ALTER TABLE Usuario_Evento ADD CONSTRAINT fk_usuario_evento_usu_email
      <br>
    FOREIGN KEY (usu_email)
      <br>
    REFERENCES Usuario (usu_email);
      <br>
  </p>
   <h3>Implementação LiquiBase. </h3>
  <p align="justify" style="font-family:roboto;">O liquibase é uma ferramenta de migração de banco de dados de código fonte aberto que permite rastrear, gerenciar e aplicar alteração na base de dados. Essa biblioteca acabou sendo útil para fazer toda migração no banco de dados, e padronizar o banco na maquina de cada desenvolvedor do sistema. Porém com a implementação do Oracle cloud junto ao projeto, essa ferramenta parou de ser utilizada por gerar muitos conflitos, e o banco de dados foi criado dentro do próprio SQL developer.</p>
  <p align="justify" style="font-family:roboto;">O primeiro passo foi adicionar a dependência da biblioteca liquibase no POM.xml do projeto</p>
  <details>
  <summary>Dependencia Liquibase no POM.xml</summary>
  <br>
   <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Vempracasa/blob/main/images/liquibase.jpg" width="1000px;" alt=""/>
  </details>
  <p align="justify" style="font-family:roboto;">Após a configuração do POM, é criado um arquivo em resources -> db -> changelog onde é feito a configuração do diretório onde será armazenado as migrações no banco de dados.</p>
  <details>
  <summary>Criação do changelog</summary>
  <br>
   <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Vempracasa/blob/main/images/changelog.jpg" width="1000px;" alt=""/>
  </details>
  <p align="justify" style="font-family:roboto;"> Após o changelog, é criado um arquivo “.sql” para adicionar as migrações, cada alteração no banco de dados é chamada de changeset, onde é possível atribuir um id, que deve ser diferente em cada alteração, e o autor daquela migração.</p>
  <details>
  <summary>Arquivo changeset</summary>
  <br>
   <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Vempracasa/blob/main/images/changeset1.jpg" width="1000px;" alt=""/>
      <br>
   <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Vempracasa/blob/main/images/changeset2.jpg" width="1000px;" alt=""/>
  </details>
   <h3>Implementação ORM utilizando o framework Hibernate </h3>
   <p align="justify" style="font-family:roboto;">O Hibernate é a solução ORM Java que consiste em uma ferramenta utilizada para realizar o mapeamento objeto-relacional de forma completa e eficiente, essa tecnologia segue a especificação JPA que define um meio para realizar esse mapeamento. O hibernate é o intermediário das interações entre os objetos do aplicativo com o banco de dados relacional, fazendo assim a conversão da programação orientada a objetos para o banco de dados.</p>
  <details>
  <summary>Adicionando a dependência do hibernate</summary>
  <br>
   <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Vempracasa/blob/main/images/hibernate.jpg" width="1000px;" alt=""/>
  </details>
  <p align="justify" style="font-family:roboto;">
O mapeamento das classes é construído através de algumas tags especificas do Hibernate, através desses dois exemplos acima conseguimos identificar tags chaves para o mapeamento, são elas:
    <br>
	  <b>@Table – Notação para especificar qual o nome da tabela no banco de dados.</b>
    <br>
	  <b>@Column – Identifica o nome da coluna. </b>
    <br>
	  <b>@Id – Identifica a “primary key”, ou seja, a coluna identificadora da tabela.</b>
    <br>
	  <b>@SequenceGenerator – Cria uma sequencia de números no banco de dados.</b>
    <br>
</p>
  <details>
  <summary>Exemplo mapeamento de classes</summary>
  <br>
   <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Vempracasa/blob/main/images/orm1.jpg" width="1000px;" alt=""/>
    <br>
    <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Vempracasa/blob/main/images/orm2.jpg" width="1000px;" alt=""/>
  </details>-
  <p align="justify" style="font-family:roboto;">Além das anotações citadas, é possível adicionar características especificas a determinada coluna. Ex:</p>
  <p align="justify" style="font-family:roboto;"><b>@Column(name = "evt_titulo", nullable = false, length = 30)</b></p>
  <p align="justify" style="font-family:roboto;">No trecho de código foi possível determinar o tamanho de caracteres a coluna aceita e também estabelecer que a coluna não aceita valores nulos.</p>
  <p align="justify" style="font-family:roboto;"><b>@Column(name = "usu_cpf", unique = true, nullable = false, length = 15)</b></p>
  <p align="justify" style="font-family:roboto;"Nesse outro trecho foi possível estabelecer que a coluna tem uma restrição de chave única (UK).</p>
  <p align="justify" style="font-family:roboto;"Durante o desenvolvimento do modelo utilizado no banco de dados, verificamos diversos relacionamento com cardinalidade n:n ( muitos pra muitos) ou seja vários elementos de uma entidade A podem se relacionar com vários elementos da entidade B e vice-versa, esses relacionamentos geram no banco de dados uma tabela de ligação, que possui o atributo identificador da primeira tabela com o identificador da segunda tabela.</p>
  <p align="justify" style="font-family:roboto;"No exemplo a seguir temos um dos vários relacionamento n:n no nosso banco de dados. As tabelas são Evento e Usuário. Ou seja, um evento pode estar ligado com diversos usuários, do outro lado um usuário pode estar ligado com diversos eventos no sistema.</p>
  <details>
  <summary>Implementação relacionamento n:n </summary>
  <br>
   <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Vempracasa/blob/main/images/manytomany1.jpg" width="1000px;" alt=""/>
    <br>
      <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Vempracasa/blob/main/images/manytomany2.jpg" width="1000px;" alt=""/>
  </details>
    <p align="justify" style="font-family:roboto;" >No mapeamento utilizamos a anotação @ManytoMany par a identificar um relacionamento muito pra muitos, após isso foi escolhido a classe que identificar a classe dominante no relacionamento, que nesse caso é a classe Evento, com isso através da anotação @JoinTable identificamos o nome da tabela de relacionamento, em “joinColumns “ informamos o nome da coluna identificadora da classe dominante (Evento) e em ”inverseJoinColumns” informamos o identificador da outra classe (Usuário).</p>
    <p align="justify" style="font-family:roboto;" >
      Na classe Usuário identificamos através do “mappedBy” que a classe é o lado dominado do relacionamento, ou seja tem função apenas de mostrar os eventos ligados aquele usuário, através da “List” chamada “eventos”.</p>
   <h3>Controle de exceção</h3>
  <p align="justify" style="font-family:roboto;" >Durante o desenvolvimento de um API ocorrem diversos erros, o padrão do framework spring é retornar uma resposta genérica para esses erros, acarretando em diversos problemas durante o teste e desenvolvimento da aplicação, levando a uma perda de tempo enorme, que na maioria das vezes é solucionado com algo simples. Com isso foi desenvolvido um controle de algumas exceções no projeto ajudando durante o seu desenvolvimento e para sua manutenção posteriormente. A primeira validação foi utilizando a implementação Bean Validator que vem junto com hibernate, essa função nós trás algumas anotações que são utilizadas para validar os atributos das classes.</p>
  
   <details>
  <summary>Controle de exceção de atributos </summary>
  <br>
      <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Vempracasa/blob/main/images/excecao1.jpg" width="1000px;" alt=""/>
  </details>
	
	<p align="justify" style="font-family:roboto;">Levando como exemplo a classe Usuário verificamos a utilização da anotação @NotBlank que informa ao spring que aquele atributo não pode estar vazio, outra anotação é @Email que verifica se o atributo “email” está em seu formato correto.</p>
	
  <details>
  <summary>Personalização de mensagens</summary>
  <br>
      <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Vempracasa/blob/main/images/excecao2.jpg" width="1000px;" alt=""/>
  </details>
    
    <p align="justify" style="font-family:roboto;">Para personalizar as mensagens que serão mostradas, foi criado um arquivo em “resources” chamado ValidationMessages.properties, esse nome é utilizado pelo spring para verificar se existe uma mensagem caso a validação falhar, caso a validação não possua mensagem personalizada será mostrado a padrão, no arquivo criado identificamos as mensagens personalizadas, após isso identificamos na anotação @NotBlank ou @Email o id dessa mensagem, como no exemplo a seguir:</p>
  
     <p align="justify" style="font-family:roboto;
@NotBlank(message = "{email.not.blank}")
 <br>
@Email(message = "{email.not.valid}")
</p>
                                    
     <p align="justify" style="font-family:roboto;">Na classe controller da aplicação utilizamos a anotação @Valid nas requisições para verificar esses atributos.</p>
  <details>
  <summary>Anotação @Valid</summary>
  <br>
      <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Vempracasa/blob/main/images/exececao3.jpg" width="1000px;" alt=""/>
  </details>
 <h3>Controle de exceção utilizando ExeceptionHandler </h3>
   <p align="justify" style="font-family:roboto;">Outra controle de execeção utilizado foi desenvolvido atráves do ExceptionHandler utilizada para tratar algumas exceções especificas do sistema e retornar a mensagem ao usuário.</p>
 <p align="justify" style="font-family:roboto;">Para isso foi criado uma classe chamada “RestExceptionHandler” que captura as exceções que foram lançadas e faz o tratamento, essa classe estende uma outra classe do spring chamada “ResponseEntityExceptionHandler”  que fornece para nós os métodos para tratar exceções interna no spring. A anotação @ControlleAdvice é uma anotação que lida com as exceções globalmente e a @ExceptionHandler é utilizada para tratar as exceções especificas.</p>
   
  <details>
  <summary> Classe RestExceptionHandler</summary>
  <br>
      <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Vempracasa/blob/main/images/excecao4.jpg" width="1000px;" alt=""/>
                                                                                                                                         <br>
       <img style="border-radius: 50%;" src="https://github.com/ferrazghs/Vempracasa/blob/main/images/excecao5.jpg" width="1000px;" alt=""/>
                                                                  
  </details>

                                                                                                                                         
  <h2 style="font-family:roboto;"> Aprendizados Efetivos :book:</h2>   
  
  ---

</body>
