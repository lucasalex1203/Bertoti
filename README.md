# Bertoti
## Atividade 1 - 19/02

  ### Realize um comentário baseado nos parágrafos abaixo:
  
  _"Within Google, we sometimes say, “Software engineering is programming integrated over time.” Programming is certainly a significant part of software : 
engineering after all, programming is how you generate new software in the first place. If you accept this distinction, it also becomes clear that we might 
need to delineate between programming tasks (development) and software engineering tasks (development, modification, maintenance). The addition of time adds an 
important new dimension to programming. Cubes aren’t squares, distance isn’t velocity. Software engineering isn’t programming._

  _We see three critical differences between programming and software engineering: time, scale, and the trade-offs at play. On a software engineering project,
engineers need to be more concerned with the passage of time and the eventual need for change. In a software engineering organization, we need to be more concerned 
about scale and efficiency, both for the software we produce as well as for the organization that is producing it. Finally, as software engineers, we are asked to 
make more complex decisions with higher-stakes outcomes, often based on imprecise estimates of time and growth."_

  Comentário: Este texto aborda a diferença entre programação e engenharia de software, destacando a importância do tempo, escala e os trade-off.
Na engenharia de software, os profissionais precisam considerar não apenas o desenvolvimento inicial, mas também modificações e manutenções futuras, 
além de dimensionar as decisões com base em estimativas imprecisas de tempo e crescimento. Nada em engenharia de software é mágica. 
É interessante observar como a programação é parte essencial da engenharia de software, mas não a resume por completo, já que envolve aspectos mais amplos e complexos.

## Atividade 2 - 26/02 

  ### De 3 exemplos de trade-off em softwares e explicá-los.
  1. Usabilidade vs. Segurança: Um trade-off comum em softwares é entre a usabilidade, tornando o software fácil e intuitivo para os usuários, e a segurança, 
garantindo que os dados e a privacidade dos usuários estejam protegidos. Por exemplo, adicionar camadas extras de segurança, como autenticação em dois fatores, 
pode tornar o processo de login mais complexo para os usuários, impactando a usabilidade.

  2. Desempenho vs. Consumo de Recursos: Muitas vezes, os desenvolvedores enfrentam o dilema de otimizar o desempenho do software, garantindo que ele execute tarefas rapidamente, 
ao mesmo tempo em que minimizam o consumo de recursos, como memória e processamento. Por exemplo, a utilização de algoritmos mais eficientes pode aumentar o desempenho do software, 
mas também pode exigir mais recursos computacionais.

  3. Flexibilidade vs. Complexidade: Ao projetar um software, os desenvolvedores podem encontrar um trade-off entre a flexibilidade do sistema, permitindo que os usuários personalizem 
e adaptem o software de acordo com suas necessidades, e a complexidade do código subjacente. Adicionar muitas opções de personalização pode tornar o software mais complexo e difícil de manter.

## Atividade 3 - 01/03

  ### 

## Atividade 4 - 25/03
Pensar em uma aplicação, onde terá que: definir a arquitetura, definir as classes UML, realizar um código java e testar.

### Idéia 

  Um aplicativo de médico virtual. Nele contém uma extensa biblioteca de informações sobre doenças, sintomas, medicamentos e até procedimentos médicos, junto com um amplo questionário de saúde com perguntas que os médicos costumam fazer aos pacientes.

  Nele, o usuário pode inserir o máximo de informações possível sobre sua saúde, como peso, idade, sexo, tipo sanguíneo, glicose, e assim por diante. A partir daí, pode iniciar uma consulta respondendo a uma série de perguntas apresentadas pelo aplicativo.

  Por exemplo, se o usuário estiver com sintomas de gripe, ele pode clicar em "consulta" e o aplicativo começará a fazer uma série de perguntas, como "quais sintomas você está sentindo?". Com base nas respostas fornecidas, o aplicativo poderá sugerir tratamentos adequados, como o uso de Paracetamol.

  No entanto, se o aplicativo não conseguir chegar a uma conclusão definitiva com base nas informações fornecidas ou se não houver informações suficientes para determinar a situação de saúde do usuário, ele poderá sugerir que o usuário consulte um médico da área correspondente.

  Além disso, o aplicativo também pode ser usado como um guia de medicamentos, permitindo que os usuários pesquisem doenças e/ou sintomas e recebam uma lista de medicamentos adequados. Quanto mais informações o usuário fornecer, mais precisos serão os resultados. Por exemplo, se o usuário fornecer informações sobre sua pressão arterial, glicose ou gravidez recente, o aplicativo poderá excluir certos medicamentos, seguindo o padrão de um médico.

  É importante ressaltar que este aplicativo não substitui uma consulta médica profissional, sendo apenas uma ferramenta para auxiliar. Assim como na engenharia elétrica, onde existem programas que facilitam a elaboração de projetos, mas não substituem a experiência e o conhecimento dos engenheiros, este aplicativo é uma ferramenta complementar aos serviços médicos tradicionais.

  ## 1. Definição da Arquitetura:
  
Arquitetura de Microservices: Pode ser benéfica devido à modularidade e escalabilidade. Cada funcionalidade (como o questionário de saúde, o bulário, etc.) pode ser um serviço separado, comunicando-se através de APIs.

Banco de Dados: Será necessário um banco de dados para armazenar informações do usuário, sintomas, doenças, remédios, etc. Um banco de dados relacional (MySQL) pode ser usado para estruturas complexas de dados.

  ## 2. Classes UML:

Usuário: Armazena informações do usuário, como peso, idade, sexo, tipo sanguíneo, etc.

Sintoma: Descreve um sintoma e suas características.

Doença: Representa uma doença com seus sintomas associados e tratamentos.

Remédio: Informações sobre remédios, como bula, contra-indicações, etc.

Consulta: Registra consultas realizadas pelo usuário, incluindo sintomas relatados e diagnósticos sugeridos.
 
  ## 3. Código Java:
Implementar classes para representar cada entidade mencionada acima.

Criar métodos para buscar informações sobre doenças, sintomas, remédios, etc., e para conduzir consultas de acordo com os sintomas relatados pelo usuário.

Desenvolver a lógica para filtrar remédios com base nas informações do usuário (pressão, glicemia, gravidez, etc.).

Criar uma interface de usuário para interagir com o aplicativo.
 
  ## 4. Testes:

Escrever casos de teste para garantir que a lógica de diagnóstico e recomendação de tratamento funcione corretamente.

Testar a integração entre os diferentes serviços do aplicativo.

Testar a interface do usuário para garantir que seja amigável e responsiva.
  
