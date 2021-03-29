# Atividade Projeto Estruturado [APE]

Acadêmico: Maicon Douglas Stelzer  
RA: 09014006  

#### 1. O que é GIT?  
GIT é um sistema de controle de versões, usado principalmente no desenvolvimento de software, porém, pode ser usado para manter histórico de alterações em qualquer tipo de arquivo. Foi inicialmente desenvolvido e projetado por Linus Torvalds para o Kernel Linux e foi adotado por muitos  outros projetos. O GIT é um software livre, distribuído sobre os termos da versão 2 da GPL, sua manutenção é atualmente supervisionada por Junio Hamano. Seu nome foi satirizado sobre o termo “Git”, uma gíria britânica para “cabeça dura, pessoas que acham que sempre têm razão, argumentativas, podendo ser também pessoa desagradável ou estúpida” e seu desenvolvimento surgiu após vários desenvolvedores do Kernel Linux decidirem desistir de acessar ao sistema do BitKeeper, por conta de ser um software proprietário.

#### 2. O que é versionamento de software?  
O versionamento de software é o processo de atribuir um nome ou numeração única, indicando o estado de um software. Esses números geralmente são atribuídos de forma crescente e indicam o desenvolvimento de melhorias ou correção de falhas. Diversas formas de versionamento são utilizadas para distinguir as versões de um software. A presença constante da computação no dia-a-dia, levou esses esquemas para contextos fora da computação, como ocorre em “Escola 2.0” e “Indústria 4.0”. Muitos projetos utilizam o esquema de versionamento “CalVer”, onde baseia-se na data de lançamento, um bom exemplo é o Ubuntu Linux, atualmente na versão 20.04 LTS e 20.10.

#### 3. Por que utilizar o Git como controle de versionamento?  
Um dos principais motivos de utilização do GIT para versionamento é sua ampla utilização em projetos   tanto proprietários como open-source, ou seja, querendo ou não você vai precisar se familiarizar com GIT, pelo fato de ser muito utilizado, são feitas melhorias e correções continuamente, mantendo-o com menos risco de BUG’s, além de que desenvolvedores já tem uma familiarização com o mesmo e isso permite uma fácil contratação de integrantes de equipe para seu projeto. Normalmente as IDE’s de desenvolvimento possuem extensões para fácil utilização do controle de versão GIT, um exemplo é o visual studio 2019, que no ínicio já apresenta um front-end para clone de projetos.

#### 4. Quais as vantagens do Git?  
Entre as principais vantagens da utilização do GIT, estão, rapidez (pelo fato dos processos serem operados localmente, deixa de ser preciso contatar o servidor para proceder operações como um commit, log ou diff), autonomia (permite trabalhar offline e em qualquer local, sendo necessário uma conexão com a rede para atualização e troca de revisões com outros repositórios), portabilidade (atualmente o GIT está disponível para BSD, SOLARIS, Darwin, Linux e Windows, permitindo desenvolvedores de diferentes sistemas operacionais trabalhar em um mesmo projeto ao mesmo tempo), branches (permite trabalhos individualizados sem atingir a principal versão do projeto, permitindo realizar melhorias ou correções totalmente diferentes ao mesmo tempo por desenvolvedores diferentes e sem que um atrapalhe o outro).

#### 5. Qual a importância da utilização do controle de versionamento no desenvolvimento de um software?  
A importância da utilização do controle de versionamento no desenvolvimento de um software está ligada com o histórico de alterações, nenhum programa pode ser considerado 100% estável e pode ser necessário a volta para uma versão antiga, porém, imagine que você não lembre o motivo pelo qual o programa parou de realizar tal funcionalidade, onde você consultaria? Bem, ai está a importância de você ter um histórico de suas alterações e um controle de versão, isso mantém o programa mais sólido, pois mesmo que ocorra problemas com a última versão, você tem como consultar o motivo pelo qual parou de funcionar e em que versão o programa continua estável para ser utilizado.

#### 6. Cite pelo menos três ferramentas de controle de versão e faça um breve detalhamento sobre cada uma delas.
CVS – Concurrent Version System (Sistema de Versões Concorrentes)
 É um sistema de versionamento que permite o trabalho com diversas versões de arquivos, sendo organizados em um diretório (local ou remotamente), mantém as versões antigas e os LOGs de quem e quando manipulou os arquivos. O CVS considera um projeto como um módulo, contendo uma hierarquia de diretórios e arquivos, um servidor CVS pode gerenciar diversos módulos, ele armazena todos os módulos em um repositório. Seu desenvolvimento foi baseado em uma versão anterior de um sistema chamado Revision Control System (RCS).

SVN – Apache Subversion
 É um sistema de versionamento desenhado especificamente para substituir o CVS por conta do mesmo possuir limitações, utilizava-se do banco de dados Berkeley BD, porém, o seu uso foi depreciado. O SVN é utilizado em grandes projetos como FreeBSD, Apache Software Foundation, Free Pascal e SourceForge, foi desenvolvido pela CollabNet em 2000 e atualmente é o projeto “top-level” da Apache Software Foundation e existem duas formas para armazenar o repositório, através de FSFS e FSX.

Mercurial
 É um sistema de versionamento multiplataforma, é implementado principalmente em Python e foi inicialmente foi escrito para sobre Linux. Seus principais objetivos são alta performance, escalabilidade, descentralização, desenvolvimento colaborativo distribuído, controle de arquivos e operações avançadas de branches + merges. Está sobre a versão 2 da licença GPL e é disponibilizado como Software Livre. Empresas como Facebook e Google fazem uso desta ferramenta para versionamento de projetos por conta de funcionar muito bem para equipes grandes.

