# microservices
O artigo fala sobre o tema da arquitetura de microserviços. Neste conteúdo, são apresentadas definições e características da arquitetura de microserviços, incluindo seu uso em aplicativos corporativos, sua organização em torno das capacidades de negócios, automação de implantação, governança descentralizada, gerenciamento de dados descentralizado, infraestrutura de automação, design para falha e design evolutivo.
As características comuns da arquitetura de microserviços incluem a componentização via serviços, organização em torno de capacidades de negócios, inteligência nos endpoints, controle descentralizado de linguagens e dados, gerenciamento de dados descentralizado, automação de infraestrutura, design para falhas e design evolutivo. O artigo foi feito por James Lewis, Lewis é um consultor principal na Thoughtworks e membro do Conselho Consultivo de Tecnologia. Ele tem interesse em construir aplicativos de pequenos serviços colaborativos e tem sido um participante ativo na crescente comunidade de microserviços há alguns anos. Ele construiu vários sistemas usando microserviços e possui experiência na integração de sistemas empresariais em grande escala. O autor do artigo alega que embora exista uma definição formal do estilo arquitetural de microserviços, podemos descrever as características comuns de arquiteturas que se enquadram no estilo: componentização via serviços, organização em torno de capacidades de negócios, inteligência nos endpoints, controle descentralizado de linguagens e dados, gerenciamento de dados descentralizado, automação de infraestrutura, design para falhas e design evolutivo. Sobre a componentização, ela é uma das características fundamentais de microserviços e é alcançada por meio de serviços. Essa abordagem envolve a quebra de um sistema grande e complexo em partes menores, independentes e modularizadas, ou seja, serviços. Um serviço em microserviços é um componente de software autônomo que pode ser implantado, dimensionado e gerenciado independentemente dos outros serviços. Cada serviço de microserviço é responsável por executar uma ou mais tarefas de negócios. Ao contrário da abordagem monolítica, em que uma alteração em um componente pode afetar todo o sistema, as alterações nos serviços podem ser feitas independentemente, reduzindo assim o risco de falhas e facilitando o gerenciamento dos componentes na produção. Sobre o conceito de produtos, não projetos, é uma abordagem sugerida pelos proponentes de microserviços. Em vez de seguir o tradicional modelo de "projeto", em que os desenvolvedores constroem um produto que é entregue ao setor de manutenção após sua conclusão, os desenvolvedores de microserviços tendem a preferir a abordagem em que uma equipe possui um produto ao longo de seu ciclo de vida completo. Essa abordagem é inspirada no modelo "build it, run it" da Amazon, onde a equipe de desenvolvimento assume total responsabilidade pelo software em produção. Isso traz os desenvolvedores para contato diário com seus usuários e com o funcionamento do software em produção, além de aumentar a responsabilidade da equipe em oferecer suporte ao software. Quando cita-se o conceito de Smart Endpoints é necessário entender que o mesmo é um dos princípios de design de microserviços, que afirma que os serviços devem ser projetados para serem inteligentes e possuírem sua própria lógica de negócios, tornando as conexões entre eles mais simples. Por outro lado, os pipelines de comunicação desses serviços, chamados de "pipes”, devem ser projetados para serem simples e transparentes. O objetivo dessa abordagem é minimizar a complexidade do sistema e facilitar a conexão entre serviços. A abordagem "smart endpoint, dumb pipes” é oposta à abordagem tradicional de SOA (Arquitetura orientada a serviços), em que sistemas de middleware complexos eram usados ​​para orquestrar serviços. Já na seção de automação de infraestrutura discute-se que é uma técnica fundamental para a construção de sistemas baseados em microserviços e é altamente enfatizada em todo o artigo. Devido ao grande número de serviços envolvidos, além de vários ambientes de execução (desenvolvimento, teste, produção), há uma necessidade crescente de automação de infraestrutura e gerenciamento de configuração para manter a velocidade e a confiabilidade das implantações de microserviços e simplificando a criação de novos serviços. Na prática, a automação da infraestrutura é alcançada por meio do uso de ferramentas de gerenciamento de configuração, como Chef, Puppet ou Ansible, que possibilitam a definição de infraestrutura como código. Assim, os desenvolvedores podem configurar facilmente os ambientes necessários para a criação de novos serviços e a execução de testes, e os administradores podem implantar e gerenciar facilmente esses serviços em toda a empresa. Generalizando sobre as partes relacionadas a design do artigo, ele discute várias partes do design necessárias para construir sistemas baseados em microserviços, incluindo a decomposição de componentes em serviços independentes, design por capacidades de negócio, controle descentralizado e gerenciamento de dados descentralizado, componentização via serviços, automação de infraestrutura, design para falha, entre outros. A ideia subjacente a esses princípios é criar um sistema que permita o desenvolvimento independente de vários serviços, tornando mais fácil gerenciar as alterações. Cada um desses princípios é discutido em detalhes, muitas vezes com exemplos práticos, para permitir o entendimento das melhores práticas de projeto de sistemas baseados em microserviços. O artigo termina dissertando se microserviços são o futuro, os autores sugerem que essa arquitetura representa uma abordagem altamente viável e eficaz para desenvolver aplicativos empresariais complexos em um ambiente de TI cada vez mais dinâmico e acelerado. O artigo apresenta diferentes pontos de vista sobre os prós e contras dos microserviços, e argumenta que os benefícios superam largamente suas desvantagens, embora a abordagem seja mais adequada para organizações grandes e complexas. Portanto, a decisão de adotar a abordagem de microserviços deve ser tomada com base em uma análise ponderada dos prós e contras, aplicando esses princípios aos requisitos específicos de negócios de cada organização.
