# Glossário Java
O objetivo deste glossário é descrever o significado de vários termos que compõem o todo o ecossistema da linguagem Java.

**Observação:** Esse Glossário está em construção, portanto pedimos a sua compreensão. E caso você queira contribuir, basta entrar em contato com o SouJava.

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/en/1/18/SouJava_logo.jpg">
</p>
--

* [O que é a linguagem Java?](#o-que-é-a-linguagem-java)
* [O que é a JVM?](#o-que-é-a-jvm)
* [O Java é Multiplataforma?](#o-java-é-multiplataforma)
* [O que é um arquivo com a extensão ".java" ?](#o-que-é-um-arquivo-com-a-extensão-java-)
* [O que é um arquivo com a extensão ".class" ?](#o-que-é-um-arquivo-com-a-extensão-class-)
* [O que é um arquivo com a extensão ".jar" ?](#o-que-é-um-arquivo-com-a-extensão-jar-)
* [O que é um arquivo com a extensão ".war" ?](#o-que-é-um-arquivo-com-a-extensão-war-)
* [O que é um arquivo com a extensão ".ear" ?](#o-que-é-um-arquivo-com-a-extensão-ear-)
* [O que é uma "api" ?](#o-que-é-uma-api-)
* [O que é o método "main" ?](#o-que-é-o-método-main-)
* [Como iniciar no desenvolvimento Java?](#como-iniciar-no-desenvolvimento-java)

Antes de descrever os vários termos do glossário, é importante falar sobre algumas informações basicas sobre o Java:

## O que é a linguagem Java?

O Java é uma linguagem que utiliza o paradigma de orientação a objetos para o desenvolvimento de software.

## O que é a JVM?

A Java Virtual Machine (JVM) é o ambiente responsável por rodar todos os sistemas desenvolvidos na linguagem java.

## O Java é Multiplataforma?

Sim. O Java é multiplataforma. A linguagem permite que o software escrito na linguagem java seja compilado e interpretado em qualquer sistema operacional.

## O que é um arquivo com a extensão ".java" ?

É o arquivo que contém o código fonte escrito na linguagem Java.

## O que é um arquivo com a extensão ".class" ?

É um arquivo criado após a compilação de um arquivo com a extensão ".java"
Após a compilação, o arquivo com a extensão ".class" já encontra-se disponível para ser interpretado pela JVM.

## O que é um arquivo com a extensão ".jar" ?

É um arquivo compactador de outros arquivos, e que é utilizado no desenvolvimnento Java. O conteúdo de um arquivo com a extensão ".jar" pode ser classes Java e/ou outros tipos de arquivos. Exemplo: arquivos com a extensão ".xml".  

## O que é um arquivo com a extensão ".war" ?

É um arquivo compactado que contém uma aplicação java e todo o seu respectivo conteúdo: arquivos HTML, classes Java, arquivos JavaScript e todos e os demais arquivos necessários para o funcionamento de uma aplicação WEB.

## O que é um arquivo com a extensão ".ear" ?

É um arquivo compactado que contém uma aplicação java e todo o seu respectivo conteúdo para uma aplicação Java EE.

## O que é uma "api" ?

É um conjunto de classes agrupadas, que podem ser fornecidas pela especificação Java (ou criadas pelo próprio desenvolvedor) e que podem ser utilizadas em algum determinado momento para auxiliar o desenvolvimento de uma aplicação Java.
Muitos desenvolvedores criam suas próprias apis e disponibilizam na internet, com o intuito de ajudar desenvolvedores que possam ter tido o mesmo problema que ele, até a construção da sua própria api.

## O que é o método "main" ?

É o método responsável por executar toda a lógica da aplicação Java.

## Como iniciar no desenvolvimento Java?

Para maiores informações sobre como se tornar um desenvolvedor na linguagem Java, acesse o site oficial no seguinte endereço: https://go.java/developer-opportunities/index.html

### _Termos do Glossário Java_

* **JDK** ---> É o kit oficial de desenvolvimento para a linguagem Java. É necessário realizar o download do mesmo e instalá-lo. O Kit contém o ambiente de desenvolvimento e também a JVM para rodar os sistemas desenvolvidos na linguagem java.
* **Java SE** ---> É o ambiente Java voltado para o desenvolvimento de aplicações desktop.
* **Java EE** ---> É o ambiente Java voltado para o desenvolvimento de aplicações WEB.
* **Java ME** ---> É o ambiente Java voltado para o desenvolvimento de aplicações móveis e integrados.
* **IDE** ---> É uma ferramenta gráfica utilizada por muitos desenvolvedores, afim de facilitar o desenvolvimento de aplicações. comumente, os desenvolvedores Java utilizam  o Eclipse ou o Netbeans.

* **JAVA_HOME** ---> É o diretório da pasta aonde encontra-se a instalação do Java. Esse caminho é inserido como uma variável de ambiente no sistema operacional.

* **CLASSPATH** ---> É o diretório atribuído a JAVA_HOME/bin. Esse caminho é inserido no PATH do sistema operacional.

* **Orientação a Objetos** ---> É o paradigma de desenvolvimento de sodtware utilizado pela linguagem Java. O conceito de orientação a objetos tem como característica, a facilidade no reaproveitamento de código para a mesma ou futuras aplicações.

* **Classe** ---> É uma coleção de dados compostos por seus atributos e métodos. Uma classe é um modelo para a criação de um objeto.

* **Classe POJO** ---> São classes dedicadas a possuirem somente atributos com seus métodos setters e getters.

* **Instância** ---> É o procidimento  necessário para criar um objeto. Muito conhecido como "dar um new em uma classe Java".

* **Objeto** ---> É construído a partir de uma classe. Ou seja, uma classe pode ser a base para a construção de diversos objetos.

* **Herança** ---> É o mecanismo que pode ser utilizado para que uma classe herde informações de uma outra classe.

* **Polimorfismo** ---> É capacidade de um objeto utilizar a referência de um outro objeto em tempo de execução.

* **Override** ---> É o mecanimo de se utilizar um método de uma classe pai. Porém, com uma escrita diferente do método original.

* **Modificadores** ---> São utilizados com intuito de gerenciar o acesso a classes, variáveis e métodos.

* **Variável** ---> É o espaço dedicado em memória para armazenar algum dado que possa ser alterado durante a utilização do sistema.

* **Constante** ---> É o espaço dedicado em memória para armazenar algum dado que não poderá ser alterado durante a utilização do sistema. É necessário utilizar a palavra reservada "final" na declaração da constante.

* **Casting** ---> É a forma como é denominda a conversão de um tipo variável para um outro tipo de variável.

* **Método** ---> É o componente responsável por executar alguma tarefa dentro de uma classe.

* **Método set** ---> É o tipo de método que executa alguma tarefa, com a intenção de repassar valores para o sistema. Esse tipo de método não utiliza a cláusula "return" ao final.

* **Método get** ---> É o tipo de método que executa alguma tarefa com a responsabilidade de retornar algum valor do sistema. Esse tipo de método utiliza a cláusula "return" ao final.

* **Construtor** ---> É o componente utilizado durante a inicialização de um objeto. O construtor pode ser implícito ou explícito.

* **Interface** ---> Uma interface contém um ou mais métodos sem as suas respectivas implementações. Cada método será implementado quando a interface for utilizada por uma classe.

* **Bloco Try Catch** ---> É a maneira como são tratadas a erros/exceções na linguagem Java.

* **Abstract** ---> São classes que não podem ser instanciadas mas que podem ser herdadas por outras classes. Cada classe abstrata também exige por definição, a declaração de ao menos um método sem corpo, contendo assim: apenas a sua assinatura.

* **Enum** ---> É um recurso do Java voltado para o armazenamento de diversas constantes. Uma enum também pode conter um construtor explícito.

* **Generics** ---> É o recurso utilizado no Java para que seja possível trabalhar com programação genérica. Com isso, classes ou interfaces podem receber um tipo genérico em tempo de execução.

* **Threads** ---> É o recurso utlizado para se trabalhar com programação concorrente. Ou seja, duas ou mais tarefas sendo executadas ao mesmo tempo.

* **Garbage Collection** ---> É o processo de gerenciamento de memória na linguagem Java.

* **Memória Heap** ---> É o espaço reservado pela JVM para realizar a alocação de objetos na memória.

* **Tipos primitivos** ---> É o tipo de valor que uma variável poderá armazenar. E os tipos primitivos podem ser: byte, short, int, long, float, double, char ou boolean.

* **Import** ---> É o termo utilizado para importar pacotes a serem utilizados em uma classe Java.

* **Package** ---> Local no qual são armazenadas as classes Java. Um projeto pode ter diversos pacotes. A boa prática indica que os pacotes armazenem classes de um determinado assunto.

* **Design patterns** ---> É uma coleção de boas práticas de desenvolvimento e que são muito utilizados pela comunidade Java ao redor do mundo.

* **Servidor WEB** ---> São ferramentas dedicadas a realização de tarefas que auxiliam o desenvolvimento WEB. Entre os servidores comumente utilizados no desenvolvimento Java WEB é o TomCat.

* **Servidor de Aplicação** ---> São ferramentas dedicadas a realização de tarefas que auxiliam o desenvolvimento WEB e que englobam toda a especificação do JAVA EE. Entre os servidores comumente utilizados estão: JBOSS e Glassfish.

* **Servlet** ---> É uma classe java responsável por algumas tarefas no desenvolvimento Java WEB. Tais como: recebimento e envio de requisições.

* **JSP** ---> É uma tecnolgia utilizada do ambiente Java, que visa facilitar a criação de páginas WEB juntamente com a programação Backend do Java.

* **Modelo MVC** ---> É um modelo de desenvolvimento de aplicações utilizado para arquitetura de software. Tal modelo é dividido em três camadas: Model, View e Controller. A camada de Modelo, representa efetivamente os dados da aplicação com suas regras de negócio. O View, representa a camada de visualização da aplicação em um dispostivo. O Controller é resposável por receber todas as requisições do usuário e gerenciá-las com o fluxo previamente determinado na aplicação.

* **DAO** ---> É um padrão de projetos utilizado do desenvolvimento de aplicações Java. Um DAO define um modelo de abstração de acesso aos dados que estão contidos em um banco de dados.

* **EJB** ---> É o componente da especificação JAVA EE escrito na linguagem Java e que roda no lado do servidor. O EJB encapsula a lógica de negócios.

* **JavaServerFaces** ---> É o componente da especificação JAVA EE que auxilia o desenvolvedor Java a construir aplicaçãoes WEB baseadas em componentes gráficos. Além de ter como base, o desenvolvimento de aplicações WEB no padrão MVC.

* **Java Persistence API** ---> É o componente da especificação JAVA EE que é voltado para o mapeamento objeto relacional no desenvolvimento de sistemas Java.

* **WebServices** ---> É a forma de se consumir informações entre sistemas ou plataformas de desenvolvimento através da interoperabilidade. Essa comunicação pode ser baseada no uso de xml para as trocas de mensagens.

* **CDI** ---> É componente da especificação JAVA EE que tem como função, a utilização da Injeção de Dependência em aplicações Java. Além de possuir outras característiscas que facilitam o gerenciamento do ciclo de vida de aplicações com outros componentes da especificação JAVA EE. Como por exemplo, EJB e JSF.

* **JMS** ---> É o componente da especificação JAVA EE que é tem como foco, facilitar o envio e recbimento de mensagens entre sistemas. Facilitando assim: a criação, o envio, o recebimento e a leitura de mensagens. E tais mensagens podem ser assíncronas ou não.

* **JTA** ---> É o componente da especificação JAVA EE que é tem como foco, o gerenciamento de transações em aplicações Java. Sua vantagem, é o gerenciamento de transações em sistemas distribuídos que possuem recursos compartilhados.

* **Segurança no JAVA SE** ---> Algumas apis são fornecidas para gerenciar a segurança das aplicações. São elas: JAAS, Java GSS, JCE, JSSE e SASL.


### [Frameworks Java](frameworks-java.md)
* [O que é o JavaServerFaces?](#o-que-é-o-javaserverfaces-)
* [O que é o Hibernate?](#o-que-é-o-hibernate-)

## O que é o "javaserverfaces" ?

É o componente da especificação JAVA EE que auxilia o desenvolvedor Java a construir aplicaçãoes WEB baseadas em componentes gráficos. Além de ter como base, o desenvolvimento de aplicações WEB no padrão MVC.

* **Ciclo de Vida** ---> O JSF tem como base, um ciclo de vida bem defindo para a construção de aplicações Web. As fases que compõem esse ciclo, são: Restore View, Apply Request Values,  Process Validation, Update Model Values, Invoke Application, Render Response.

* **Expression Language** ---> É utilizada em páginas HTML. Sua função é se comunicar com os managead Beans do JSF.

* **Managed Beans** ---> São anotações utlizadas em classes Java. Sua função é facilitar a comunicacação entre arquivos HTML e classes Java, seja na inserção ou para consulta de dados do sistema. Comumente se comunica com os DAOs do sistema. Os Managed Beans também possuem definição de escopo. É necessário customizar o tipo de escopo para cada Managed Beans.

* **AJAX** ---> O AJAX permite ao desenvolvedor, entre as muitas opções de comunicação com  o servidor, a realização de atividades assíncronas. Como por exemplo, a atualização de páginas de internet de acordo com determinadas ações do usuário. Evitando assim, a necessidade de toda atualização da tela do sistema. Tornando assim, a navegabilidade do usuário mais amigável. E o melhor de tudo isso, é que o JSF já traz o Ajax incorporado em sua implementação.

* **Facelet** ---> É o recurso utilizado para a construção de templates em aplicações Web com o JavaServerFaces. Esse recurso, evita a duplicação de código em diversas partes da aplicação.

* **Conversores** ---> Essa funcionalidade é útil para a conversão de tipos durante uma requisição ou solicitação feita pelo usuário, por exemplo.

* **Validadores** ---> São úteis para validar informações inseridas por um usuário.


## O que é o "hibernate" ?
 
 É um frammework que tem como objetivo, utilizar o mapeamento objeto-relacional(ORM) em uma aplicação. Seja ela, uma aplicação web. Seja ela, uma aplicação desktop. 
 Com esse tipo de mapeamento, é o possível aumentar o nível de abstração entre uma aplicação e o banco de dados. Tornando assim, a aplicação mais independente da linguagem SQL espefífica que cada banco de dados utiliza. 
 
 * **persistence.xml** ---> É o arquivo de configuração do Hibernate. Esse arquivo contém informações essenciais para o uso do frameqork em uma aplicação. Tal arquivo deve ser preenchido corretamente com informações do tipo: qual driver será utilizado para a conexão com o banco de dados, o tipo de dialeto utilizado pelo banco de dados, a url de endereço que identifica o local do banco de dados, usário e senha que serão utilizados para se conectar com o banco, entre outras informações importante para a conexão com o banco de dados.

* **@Entity** ---> É a anotação utilizada na classe POJO da aplicação. Dessa forma, as classes que possuírem tal anotação: serão tratadas como entidades do banco de dados.
* **EntityManagerFactory** ---> É responsável por gerenciar e disponibilizar métodos que podem ser utilizados em transações com o banco de dados.

