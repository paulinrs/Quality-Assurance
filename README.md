<div align="center">
<img src="https://user-images.githubusercontent.com/104467309/197521037-26b20ec7-f942-41fe-83ca-dac366c30007.jpg" width="800">

##

# QA Quality Assurance: o que é?   

QA – Quality Assurance significa garantia de qualidade em português, e se refere a uma série de procedimentos e testes realizados para atestar que um produto funcione corretamente. 

Geralmente, na reunião de kickoff, os gestores do projeto, equipe de desenvolvimento e cliente debatem para entender melhor o produto pretendido e, desta forma, alinhar as expectativas.

Até a entrega, muitos testes são realizados para encontrar possíveis falhas, defeitos e qualquer tipo de problema que comprometa a experiência do usuário. 

Em resumo, o Quality Assurance envolve toda uma checagem da parte de profissionais especializados que irão averiguar se os padrões e especificações solicitadas pelo cliente foram cumpridas.  

Seja um software, aplicativo, programa ou website, todo produto precisa ser testado antes da entrega, e é o processo de QA que vai garantir as boas funcionalidades de cada projeto.    


##
# Fundamentos do Teste de Software

## Conceituando Teste de Software

O teste é composto por diversas atividades: Planejamento e controle, Análise e modelagem, Implementação e execução, Avaliação dos critérios de saída e relatórios, e Atividades de encerramento de teste. Além disso, o teste também pode incluir a revisão de documentos, incluindo o código fonte, e a análise estática. Essas atividades podem acontecer de forma concorrente e não necessariamente numa ordem específica.

Como podemos notar, analisando as atividades que fazem parte dos testes, podemos concluir que a execução do teste é apenas uma das atividades que devem ser realizadas, ainda temos os planos, a modelagem e a avaliação de resultados.

Os testes ainda podem ser definidos através de duas fronteiras: dinâmicos ou estáticos. O teste dinâmico consiste nas atividades de planejamento, execução e controle. No teste dinâmico o software necessita ser executado. Já o teste estático consiste nas atividades de revisão (na documentação do projeto e código fonte), inspeção (na documentação do projeto e código fonte) e análise estática de código. O teste dinâmico é o mais utilizado, mas também tende a ter um custo mais alto, pois o software já está sendo executado. Por isso é sempre importante anteciparmos os testes no ciclo de vida para prevenir defeitos no código. Se os testes iniciarem logo na fase de requisitos, por exemplo, a revisão de documentos ajudaria nessa prevenção e evitaria diversas outras etapas com erros.

Algumas pessoas acham que o teste serve para confirmar que o software funciona. Isso é totalmente errado, o teste serve para encontrar defeitos, prevenir defeitos, testar o nível de qualidade do software ou ainda prover informações para uma tomada de decisão.

Os diferentes tipos de teste possuem também diferentes objetivos. No teste feito em desenvolvimento através dos testes de componentes, integração e de sistemas o objetivo é causar falhas, de modo que os defeitos possam ser identificados e resolvidos. No teste de aceite junto ao usuário estaremos mais focados em confirmar se o sistema está funcionando conforme esperado pelo usuário. Os testes de manutenção são utilizados para verificar se novos erros não foram introduzidos durante o desenvolvimento das mudanças e, por fim, os testes operacionais avaliam características como confiabilidade e disponibilidade.

## A Necessidade de Testar

Antigamente os sistemas de computadores não tinham nenhuma ou quase nenhuma influência nos negócios das organizações. Atualmente este contexto mudou radicalmente e as falhas em softwares podem acarretar sérios prejuízos financeiros, danos materiais, perda de reputação ou até mesmo causar mortes. Os softwares estão presentes em praticamente todos eletrodomésticos, motores, automóveis, etc. Por exemplo, temos software presente em elevadores que fazem parte de diversos edifícios, em aparelhos de televisão, nos automóveis que usamos no dia a dia, em celulares, em eletrodomésticos como micro-ondas, geladeira, etc. Além disso, temos também muitas aplicações críticas que se falharem podem causar sérios danos. Exemplo dessas aplicações são os softwares de controle que estão presentes nas usinas nucleares, softwares que estão presentes em aeronaves ou embutido em mísseis e radares, software que agem no controle de pacientes que são tratados em casa ou em hospitais, etc. Alguns dos grandes desastres causados por software estão: a explosão do foguete Ariane quarenta segundos após a decolagem em 1996 que foi causado por um erro no projeto do software que fez com que o foguete desviasse de sua rota e explodisse; outro grave acidente foi com o Airbus A380 devido as incompatibilidades das diferentes versões usadas do software de projeto e projetos mecânicos CATIA, enquanto os sócios franceses utilizavam a última versão, a fábrica alemã não tinha ainda atualizado a mesma; Recentemente um novo sistema desenvolvido pela Siemens para controlar a emissão de passaportes sem testes suficientes e sem pessoal qualificado estragou com as férias de mais de meio milhão de britânicos. Atualmente diversos outros problemas causados por software também resultaram em diversos problemas, como no Banco Itaú, TAM, entre outros. Estima-se que os defeitos de software tenham custado cerca de 60 bilhões de dólares no ano de 2007, de acordo com o National Institute OS Standards and Tecnology.

Dessa forma, tornou-se fundamental o teste de software nos dias atuais.

Os testes de software são realizados, pois um humano independe da sua qualificação ou experiência pode cometer um erro na especificação ou na documentação que por sua vez produzirá um defeito no código, que se for executado produzirá uma falha visível. Portanto, temos aqui três conceitos muito importantes: erro, defeito e falha. Também podemos observar que um software pode conter defeitos, mas nunca falhar, pois para falhar ele precisa ser executado ou observado. Além disso, o defeito é um estado do software causado por um erro.

O erro cometido pelo ser humano advém de diversos fatores como mudanças tecnológicas, falhas na comunicação, problemas no processo, complexidade do sistema, pressão, prazo muito curto, etc. Algumas vezes as falha são causadas por condições no ambiente como radiação, poluição, etc., que podem influenciar a execução do software devido alteração das condições de hardware. Um exemplo disso é uma corrente elétrica muito oscilante que pode comprometer um equipamento que por sua vez pode levar a um defeito numa parte do HD onde se encontra um software ou até mesmo ao travamento do sistema operacional do equipamento acarretando outros problemas nos softwares desse sistema.

O teste se faz ainda mais necessário para construirmos uma confiabilidade no sistema. A confiabilidade é uma probabilidade que o software não causará uma falha no sistema por um tempo e condições determinadas. Ou seja, um software poderá ter defeitos, mas mesmo assim ser confiável. Isso porque um software nunca será totalmente livre de defeitos, partes que não foram testadas o suficiente ou utilizadas certamente terão deslizes, mas é importante que as partes principais ou mais específicas estejam funcionando corretamente para o cliente. Por isso a confiabilidade tende a aumentar no decorrer do tempo quanto mais o software for utilizado e executado. Quanto menos falhas forem ocorrendo ao longo do tempo mais confiável o software vai se tornando.

Por fim, os testes também precisam ter certo nível de independência. Dizemos que um teste com Baixo nível de independência é aquele onde os testes são realizados pelo próprio programador que escreveu o código. Esse é o pior dos casos. O nível Médio de independência é aquele em que os testes são realizados por um programador diferente daquele que fez o software. Um nível Alto de independência e, dessa forma, mais desejado, é aquele em que os testes são realizados por uma pessoa ou por uma equipe que é independente da equipe de desenvolvimento. Por fim, um nível ainda mais alto de independência seria um teste que fosse totalmente gerado por ferramentas e que não houvesse nenhuma intervenção humana. Obviamente que este último nível de independência é impossível de ser alcançado, por isso a melhor forma de testar é aquele teste realizado por uma equipe de testes independentes ou em alguns casos por uma fábrica de testes como aquelas empresas que são especializadas apenas em testar softwares sem que precisa-se arcar com os altos custos de contratação, treinamento, atualização da equipe e das tecnologias e ferramentas.

Outra situação que causam confusões na área de teste de software é a diferença entre o conceito de depuração de código e teste. É sempre bom deixar claro que ambas são atividades diferentes. Enquanto que os testes procuram demonstrar as falhas, a depuração concentra-se em identificar a causa de um defeito. As duas atividades também possuem diferentes responsabilidades, pois, testadores testam enquanto que desenvolvedores depuram. Basicamente na depuração temos uma ferramenta que é utilizada por programadores que reproduzem a falha investigando o estado dos objetos procurando pelo defeito.

Por fim, uma pergunta recorrente que todos sempre fazem é: quanto nós devemos testar? Para responder esse tipo de pergunta sempre devemos levar em consideração quatro níveis de risco: o risco técnico, risco do negócio e o risco do projeto que também inclui restrições do projeto como tempo e orçamento.

## Relação entre Qualidade e Teste

Qualidade é um conceito muito relativo e depende do produto que está sendo analisado, depende do observador, e temos ainda diversos aspectos que são levados em conta.

Existem diversos conceitos de qualidade, um deles é definido pela norma NBR ISO 9000: "Qualidade é a totalidade das características de uma entidade que lhe confere a capacidade de satisfazer as necessidades explícitas e implícitas".

Agora que conhecemos uma definição básica sobre a qualidade em geral, se trazermos a qualidade para o software teríamos a seguinte afirmação: “Qualidade de Software é aplicar os conceitos referentes a qualidade ao software”. O autor Pressman, um dos mais renomados autores de engenharia de software, define qualidade aplicada ao software de forma mais detalhada como: "Qualidade é a conformidade a requisitos funcionais e de desempenho explicitamente declarados, a padrões de desenvolvimento claramente documentados e a características implícitas que são esperadas de todo software profissionalmente desenvolvido”. A norma ISO/IEC 9126 vai um pouco mais longe e define que um software de qualidade deve ser correto, manutenível, confiável, flexível, eficiente, testável, integro, portável, fácil de usar, reutilizável e interoperável.

De forma sumarizada qualidade é o grau a qual um sistema atende às necessidades dos usuários de forma confiável, acessível, segura, no tempo certo e com o menor custo.

Outra definição bastante diversificada é a de teste, segundo o autor Glenford Myers testar é analisar um programa com a intenção de descobrir erros e defeitos. Outras definições também são dadas para o teste, porém é interessante saber também a definição de teste dada pelo ISTQB: “Processo que consiste em todas as atividades do ciclo de vida, tanto estáticas quanto dinâmicas, voltadas para o planejamento, preparação e avaliação de produtos de software e produtos de trabalho relacionados a fim de determinar se elas satisfazem os requisitos especificados e demonstrar que estão aptas para sua finalidade e para a detecção de defeitos.”. Podemos verificar que o ISTQB sugere uma definição um pouco mais ampla.

Uma pergunta a ser respondida é: Será que com teste podemos aumentar a qualidade do software?

A resposta é não. O teste ajuda a medir como está a qualidade do software e reduz os riscos de ocorrerem problemas aumentando a confiabilidade do software. A qualidade é medida através de requisitos funcionais e não funcionais, sendo que para os requisitos não funcionais podemos realizar os testes de confiabilidade (capacidade do produto se manter no nível de desempenho nas condições estabelecidas), usabilidade (capacidade do produto de software ser compreendido, seu funcionamento aprendido, ser operado e ser atraente ao usuário), eficiência (capacidade do tempo de execução e os recursos envolvidos serem compatíveis com o nível de desempenho do software), manutenibilidade (capacidade ou facilidade do produto de software ser modificado, incluindo tanto as melhorias ou extensões de funcionalidade quanto as correções de defeitos, falhas ou erros), portabilidade (capacidade do sistema ser transferido de um ambiente para outro) e funcionalidade (capacidade de um software prover funcionalidades que satisfaçam o usuário em suas necessidades declaradas e implícitas, dentro de um determinado contexto de uso). Assim, o teste é fundamental para a avaliação do software desenvolvido, entretanto, testar um software não é uma atividade trivial, e exige conhecimentos, habilidades e infraestrutura.

Portanto, somente testar não garante a qualidade do software, mas ajuda a diagnosticar como está a qualidade deste software.

## Os Princípios do Teste

# O teste possui sete princípios básicos, são eles: 
### Teste Demonstra a Presença de Defeitos
onde neste principio afirma-se que o teste pode mostrar a presença de defeitos num software, mas jamais pode provar que eles não existem, e mesmo que nenhum defeito seja encontrado não é provado que ele esteja perfeito ou livre de defeitos; 
### Teste Exaustivo é Impossível
em que neste principio afirma-se que testar tudo não é a melhor forma de testar, sendo muitas vezes impossível, exceto em alguns casos raros. Esse tipo de teste é caro, requer muito tempo e muitas pessoas envolvidas; 
### Teste Antecipado é o terceiro principio
onde se diz que o teste deve iniciar o mais cedo possível no ciclo de desenvolvimento de software, isso porque quanto mais tarde levarmos para descobrir um erro mais caro custará para conserta-lo; 
### Agrupamento de Defeitos 
é o quarto principio na qual se afirma que um número pequeno de módulos possui a maioria dos defeitos descobertos durante o teste ou então exibem a maioria das falhas operacionais; 
### O Paradoxo do Pesticida
é o quinto principio que afirma que um conjunto de teste que são repetidos várias vezes não encontrarão novos defeitos após certo tempo, devido a isso os testes devem sempre passar por revisão e ser atualizados constantemente; 
### Teste Depende do Contexto
é o sexto principio que afirma que os testes são realizados de diferentes formas conforme o contexto de cada um; Por fim, 
### A Ilusão da Ausência de Erros
é o sétimo principio onde se afirma que encontrar e consertar defeitos não ajuda se o sistema construído não atende às expectativas dos usuários.
  
## Atividades do Teste  
  
O “Planejamento e Controle” do teste é a primeira atividade realizada. Nesta atividade o Planejamento consiste em definir quais são os objetivos do teste e especificamos quais as atividades necessárias para alcançar esses objetivos. Nesta etapa de Planejamento também especificamos o escopo do projeto de forma a detalhar as funcionalidades do software a serem testadas. O Planejamento tem como saída o Plano de teste que é um documento com a descrição do escopo, meta, objetivos, recursos necessários e cronograma. Após isso o Controle do teste acontece em todas as atividades como uma forma de comparar o progresso atual contra o que foi planejado reportando o status atual e os desvios que estão ocorrendo em relação ao plano definido. Portanto, o Controle monitora o progresso durante todo o projeto. Podemos notar que a atividade de Planejamento e de Controle são atividades voltadas à gestão, por isso normalmente são executadas por um gerente de teste ou desenvolvimento dependendo do projeto.

A “Análise e Modelagem” do teste têm como objetivo transformar os objetivos em condições e modelos de teste. Diversas atividades principais são especificadas nesta etapa como: revisão da base de testes, avaliação da testabilidade dos requisitos e do sistema, identificação e priorização dos testes com base na analise das especificações, projeção e priorização dos casos de testes de alto nível, identificação das necessidades de dados para efetuar os testes, planejamento e preparação do ambiente de teste, criação da rastreabilidade entre requisitos e casos de teste.

Portanto, nesta etapa identificaremos tudo que deve ser testado analisando a aplicação como um todo (Análise) e depois modelamos como devemos testar (Modelagem). Como podemos notar, na análise identificamos o que necessita ser testado e na modelagem detalhamos como iremos testar. Além disso, também obteremos a infraestrutura necessária para os testes.

Na “Implementação e Execução” do teste é onde preparamos e configuramos o ambiente, criaremos scripts de testes de acordo com os casos de teste que serão finalizados e priorizados, criaremos os dados de teste, verificaremos e atualizamos a rastreabilidade bidirecional entre a base de teste e os casos de teste, e, por fim, executaremos os testes manualmente ou com ferramentas e registraremos os resultados da execução comparando resultados obtidos com os esperados. Os casos de teste especificam em detalhe como testaremos uma determinada funcionalidade do sistema descrevendo o que será testado, os dados de entrada necessários, quais os retornos esperados, etc.

A “Avaliação do Critério de Saída e Relatório” é onde avaliamos a execução do teste dados os objetivos definidos no planejamento de teste, avaliamos se serão necessários mais testes ou se o critério de saída deveria ser alterado e, por fim, elaboramos um relatório de teste resumido para todos os interessados no projeto. Os critérios de saída podem ser definidos através de uma restrição de tempo, número de requisitos cobertos, porcentagem de testes executados, número de defeitos que permanecem, ou ainda se todos os casos de testes foram executados ou aprovados, etc. Basicamente esses critérios são acordados com os interessados e permite que um processo seja considerado como completado.

A última etapa é a “Atividade de Encerramento” de teste em que coletamos todos os dados de todas as outras atividades para consolidar a experiência obtida, o testware (toda documentação gerada pelo processo de teste como planos de teste, condições de teste, casos de teste, base de teste utilizada, etc), fatos e números consolidados. Nesta etapa ainda checamos se todos os entregáveis planejados foram entregues, fechamos relatórios e incidentes, documentamos o aceite do sistema, finalizamos e arquivamos o testware, ambientes de teste, infraestrutura de teste para reuso, analisamos lições aprendidas para determinar as mudanças para futuros projetos, e melhoramos a maturidade do teste com as informações coletadas.  

## Testadores de Software  

Os testadores encontram defeitos com o intuito de poupar tempo, reduzir riscos, reduzir custos e aumentar a produtividade.

Testadores em geral possuem uma visão diferente dos desenvolvedores como: pessimismo, olhar crítico, atencioso aos detalhes e experiência em encontrar defeitos. Quando o software é testador por um testador também temos alguns benefícios como visão independente (sem influência do autor), capacitação e treinamento específico para testar.

Infelizmente os testadores são vistos como profissionais “malvados”, pois, ao invés de criarem eles realizam tarefas destrutivas, isso porque muitas vezes o código precisa ser refeito ou reconstruído. Isso ocorre devido as diferentes perspectivas de cada um, onde programadores procuram construir os softwares de acordo com os requisitos dos usuários e focam em fazer esse software funcionar, além disso, trabalham muito tempo e muitas horas para isso, por outro lado, testadores se preocupam que o usuário tenha um sistema funcional e confiável. Dessa forma, é muito importante que os testadores tenham uma boa comunicação com os desenvolvedores para não causar atritos ou constrangimentos entre as equipes. Para isso, além de uma boa relação que é construída no dia a dia e em cada comunicação que é feita entre as partes, as informações também precisam ser sólidas sobre qual é o defeito que está sendo apresentado, os erros encontrados devem ser reportados de forma neutra, focar no ocorrido ao invés na pessoa que criou, interpretar a reação da pessoa que está recebendo a notícia e confirmar que a pessoa realmente entendeu o que aconteceu. A informação do defeito ajuda o desenvolvedor a encontrar o defeito o mais rápido possível e a ampliar os conhecimentos sobre o software.

Além dos testadores existem também outros papeis associados ao teste de software, são eles: O líder ou gerente do projeto de testes é aquele que é responsável pela liderança de um projeto de teste, seja um projeto novo ou um projeto que está em manutenção. Já o engenheiro ou arquiteto de teste é o técnico responsável pelo levantamento de necessidades relacionadas com a montagem da infraestrutura de teste, incluindo o ambiente de teste, a arquitetura de solução, as restrições tecnológicas e as ferramentas de teste. O engenheiro de teste também é responsável pela liderança técnica do trabalho de teste e pela comunicação entre a equipe de teste e a equipe de projeto ou equipe de desenvolvimento. O analista de teste é o técnico responsável pela operacionalização do processo de teste. Os analistas devem seguir as orientações do gerente de teste ou do arquiteto de teste para detalhar a forma de execução dos testes e as condições de teste necessárias além de focar o trabalho nas técnicas de teste adequadas à fase de teste trabalhada. O testador, como já verificamos, é o técnico responsável pela execução de teste sempre observando as condições de teste e respectivos passos de teste documentados pelo analista de teste evidenciando sempre os resultados de execução. Por fim, o automatizador de teste é o técnico responsável pela automação de situações de teste através de ferramentas sempre devendo observar as condições de teste e respectivos passos de teste documentados pelo analista de teste e automatizando a execução desses testes na ferramenta utilizada. Normalmente são gerados scripts de teste que permitam a execução de ciclos de teste desde que sejam garantidas as mesmas condições iniciais do ciclo de teste como os valores de dados, estados dos dados, estados do ambiente, etc.
  
  ### Referências
  
  Certified Tester Foundation Level Syllabus, disponível em: http://www.bstqb.org.br/4
  
  JSR-000345 Enterprise JavaBeansTM 3.2, Disponível em https://jcp.org/aboutJava/communityprocess/final/jsr345/index.html
