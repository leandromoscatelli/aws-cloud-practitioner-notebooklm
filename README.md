# aws-cloud-practitioner-notebooklm

[OBJETIVO]
NotebookLM com conteúdos que serão base para a prova de certificação da AWs Cloud Foundation do módulo 1 ao 6 (por limitação de fontes). As fontes foram retiradas do curso AWS Cloud Practitioner Essentials (Português) (https://skillbuilder.aws/learn/94T2BEN85A/aws-cloud-practitioner-essentials-portugus/V1ZR7QAGKS?parentId=1FKNHGZFR3) 

https://notebooklm.google.com/notebook/05717a21-0e5f-43c2-8824-88167c03f31e

[FONTES]

https://aws.amazon.com/what-is-cloud-computing/
https://aws.amazon.com/compliance/shared-responsibility-model/
https://aws.amazon.com/about-aws/global-infrastructure/regions_az/
https://aws.amazon.com/products/compute
https://docs.aws.amazon.com/whitepapers/latest/aws-overview/compute-services.html
https://aws.amazon.com/ec2/
https://aws.amazon.com/ec2/instance-types/
https://aws.amazon.com/ec2/pricing/
https://aws.amazon.com/ec2/autoscaling/
https://aws.amazon.com/elasticloadbalancing/
https://aws.amazon.com/sns/
https://aws.amazon.com/sqs/
https://aws.amazon.com/containers/services/
https://aws.amazon.com/ecr/
https://aws.amazon.com/ecs/
https://aws.amazon.com/eks/
https://aws.amazon.com/fargate/
https://aws.amazon.com/elasticbeanstalk/
https://aws.amazon.com/batch/
https://docs.aws.amazon.com/lightsail/latest/userguide/what-is-amazon-lightsail.html
https://docs.aws.amazon.com/outposts/latest/server-userguide/what-is-outposts.html
https://aws.amazon.com/about-aws/global-infrastructure/
https://aws.amazon.com/edge/
https://aws.amazon.com/cloudformation/
https://aws.amazon.com/vpc/
https://docs.aws.amazon.com/vpc/latest/userguide/configure-subnets.html
https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Internet_Gateway.html
https://docs.aws.amazon.com/vpn/latest/s2svpn/how_it_works.html
https://aws.amazon.com/vpn/client-vpn/
https://aws.amazon.com/vpn/site-to-site-vpn/
https://docs.aws.amazon.com/vpc/latest/privatelink/what-is-privatelink.html
https://aws.amazon.com/directconnect/
https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html
https://docs.aws.amazon.com/vpc/latest/userguide/vpc-security-groups.html
https://aws.amazon.com/route53/what-is-dns/
https://aws.amazon.com/route53/
https://aws.amazon.com/cloudfront/
https://aws.amazon.com/global-accelerator/
https://aws.amazon.com/transit-gateway/
https://docs.aws.amazon.com/vpc/latest/userguide/vpc-nat-gateway.html
https://aws.amazon.com/api-gateway/
https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/InstanceStorage.html
https://aws.amazon.com/ebs/
https://docs.aws.amazon.com/ebs/latest/userguide/ebs-snapshots.html
https://aws.amazon.com/s3/
https://aws.amazon.com/s3/storage-classes/
https://docs.aws.amazon.com/AmazonS3/latest/userguide/creating-buckets-s3.html
https://aws.amazon.com/efs/
https://aws.amazon.com/fsx/

[Prompts]
>>> Considere o contexto de prova de certificação AWS Cloud Foundation, me traga tópicos de informações, como um checklist do que preciso saber para a prova

>>>Para a prova de certificação AWS Cloud Foundation, você deve dominar conceitos fundamentais de nuvem, a infraestrutura global da AWS, os principais serviços e o modelo de segurança. Abaixo está um checklist detalhado com os tópicos essenciais:
1. Conceitos de Computação em Nuvem
Definição: Entenda a entrega sob demanda de recursos de TI via internet com pagamento conforme o uso
.
Vantagens da Nuvem:
Agilidade: Acesso rápido a tecnologias para inovação
.
Elasticidade: Redimensionar recursos conforme a demanda
.
Economia de custos: Trocar gastos fixos por variáveis e aproveitar economias de escala
.
Implantação global: Capacidade de implantar aplicações em várias regiões em minutos
.
Modelos de Nuvem: Diferencie IaaS (Infraestrutura), PaaS (Plataforma) e SaaS (Software)
.
2. Infraestrutura Global da AWS
Regiões e Zonas de Disponibilidade (AZs): Regiões são locais físicos ao redor do mundo que agrupam AZs
. AZs consistem em um ou mais data centers discretos com energia e redes redundantes
.
Pontos de Presença (Edge Locations): Usados pelo Amazon CloudFront para entregar conteúdo com baixa latência
.
Serviços Híbridos e de Borda: Conheça o AWS Outposts (infraestrutura AWS local), AWS Local Zones (computação próxima a usuários finais) e AWS Wavelength (baixa latência em redes 5G)
.
3. Modelo de Responsabilidade Compartilhada
Segurança "da" Nuvem (AWS): A AWS é responsável pela proteção da infraestrutura global (hardware, software, redes e instalações)
.
Segurança "na" Nuvem (Cliente): O cliente é responsável por configurar o sistema operacional convidado, softwares, firewalls de rede (grupos de segurança) e gerenciamento de dados/criptografia
.
Controles Compartilhados: Exemplos incluem o gerenciamento de patches (AWS cuida da infraestrutura, cliente cuida do SO/apps) e configuração
.
4. Serviços de Computação (Compute)
Amazon EC2: Servidores virtuais escaláveis
. Conheça os modelos de compra: On-Demand (sem compromisso), Spot (descontos de até 90% para cargas tolerantes a falhas), Instâncias Reservadas e Savings Plans (compromissos de longo prazo)
.
AWS Lambda: Execução de código sem servidor (serverless) em resposta a eventos
.
Containers: Amazon ECS e Amazon EKS (Kubernetes gerenciado)
. O AWS Fargate permite rodar containers sem gerenciar servidores
.
Implantação: AWS Elastic Beanstalk para implantar e escalar aplicações web automaticamente
.
Lightsail: Solução simplificada de servidor privado virtual para projetos menores
.
5. Armazenamento (Storage)
Amazon S3: Armazenamento de objetos com alta durabilidade (11 noves)
. Conheça as classes de armazenamento como Standard, Intelligent-Tiering, Standard-IA e Glacier para arquivamento
.
Amazon EBS: Armazenamento em bloco persistente para instâncias EC2, suportando snapshots incrementais
.
Amazon EFS: Sistema de arquivos elástico e compartilhado para computação baseada em Linux
.
Amazon FSx: Sistemas de arquivos gerenciados para Windows e cargas de alta performance (Lustre)
.
6. Redes e Entrega de Conteúdo
Amazon VPC: Rede virtual isolada onde você define sub-redes, tabelas de rotas e gateways
.
Segurança de Rede:
Grupos de Segurança: Atuam como firewalls para instâncias (stateful)
.
NACLs (Network Access Control Lists): Controlam o tráfego no nível da sub-rede (stateless)
.
Conectividade: AWS Direct Connect (conexão dedicada), Site-to-Site VPN (túnel criptografado) e Transit Gateway (hub central de redes)
.
DNS e Aceleração: Amazon Route 53 (serviço de DNS) e AWS Global Accelerator (melhora performance global via IPs estáticos)
.
7. Integração e Mensageria
Amazon SQS: Filas de mensagens para desacoplar microserviços
.
Amazon SNS: Serviço de notificações Pub/Sub (aplicação para aplicação ou para pessoas)
.
Amazon API Gateway: Criação e gerenciamento de APIs em qualquer escala
.
8. Gestão de Custos e Faturamento
Precificação: O modelo básico é pagamento conforme o uso (pay-as-you-go)
.
Ferramentas: Use o AWS Pricing Calculator para estimar custos mensais de recursos
.
Faturamento por segundo: Disponível para instâncias EC2 rodando sistemas como Linux e Windows
.

>>>Me traga os serviços AWS em uma lista de tópicos e um resumo de no máximo 2 linhas o recurso

>>>Aqui estão os principais serviços da AWS, organizados por categorias, conforme descrito nas fontes fornecidas:
Computação (Compute)
Amazon EC2 (Elastic Compute Cloud): Fornece capacidade de computação segura e redimensionável por meio de servidores virtuais na nuvem
.
AWS Lambda: Permite executar código sem provisionar ou gerenciar servidores, pagando apenas pelo tempo de computação consumido
.
Amazon Lightsail: Plataforma simplificada que oferece tudo o que é necessário para lançar sites ou aplicações rapidamente com preços baixos e previsíveis
.
AWS Elastic Beanstalk: Serviço de fácil uso para implantar e escalar aplicações web desenvolvidas em várias linguagens em servidores familiares
.
AWS Fargate: Mecanismo de computação sem servidor para contêineres que remove a necessidade de gerenciar a infraestrutura subjacente
.
AWS Batch: Gerencia e escala centenas de milhares de trabalhos de computação em lote de forma eficiente em toda a gama de serviços AWS
.
AWS App Runner: Serviço totalmente gerenciado para implantar rapidamente aplicações web e APIs conteinerizadas em escala
.
Armazenamento (Storage)
Amazon S3 (Simple Storage Service): Serviço de armazenamento de objetos projetado para oferecer durabilidade, escalabilidade e segurança líderes na indústria
.
Amazon EBS (Elastic Block Store): Oferece volumes de armazenamento em bloco de alto desempenho para uso com instâncias do Amazon EC2
.
Amazon EFS (Elastic File System): Fornece um sistema de arquivos compartilhado, sem servidor e totalmente elástico para serviços de computação AWS
.
Amazon FSx: Facilita o lançamento e escalonamento de sistemas de arquivos ricos em recursos e de alto desempenho, como Windows File Server e Lustre
.
Redes e Entrega de Conteúdo (Networking & Content Delivery)
Amazon VPC (Virtual Private Cloud): Permite definir e lançar recursos da AWS em uma rede virtual isolada logicamente, garantindo controle total sobre o ambiente
.
Amazon CloudFront: Rede de entrega de conteúdo (CDN) que distribui dados de forma segura com baixa latência e altas velocidades de transferência
.
Amazon Route 53: Serviço de DNS em nuvem altamente disponível e escalável, projetado para rotear usuários para aplicações de internet
.
AWS Direct Connect: Cria uma conexão de rede dedicada entre o ambiente local e a AWS, ignorando a internet pública
.
AWS Global Accelerator: Melhora a disponibilidade e o desempenho das aplicações usando a rede global da AWS para rotear o tráfego
.
AWS Transit Gateway: Atua como um hub central para conectar milhares de VPCs e redes locais de maneira simplificada
.
Amazon API Gateway: Serviço gerenciado para que desenvolvedores criem, publiquem e protejam APIs em qualquer escala
.
AWS Site-to-Site VPN: Estabelece conexões seguras entre o seu centro de dados ou escritório e os recursos na AWS por meio de túneis criptografados
.
AWS PrivateLink: Fornece conectividade privada entre VPCs e serviços, sem expor o tráfego à internet pública
.
Contêineres (Containers)
Amazon Elastic Container Service (ECS): Serviço de orquestração de contêineres totalmente gerenciado que facilita a execução de aplicações conteinerizadas
.
Amazon Elastic Kubernetes Service (EKS): Serviço gerenciado que facilita a execução do Kubernetes na AWS sem a necessidade de gerenciar o plano de controle
.
Amazon Elastic Container Registry (ECR): Registro de contêineres totalmente gerenciado que permite armazenar, gerenciar e implantar imagens de contêineres
.
Integração de Aplicações e Gestão
Amazon SQS (Simple Queue Service): Serviço de filas de mensagens totalmente gerenciado para desacoplar e escalar microsserviços e sistemas distribuídos
.
Amazon SNS (Simple Notification Service): Serviço de mensagens Pub/Sub para comunicações entre aplicações (A2A) e para pessoas (A2P)
.
AWS CloudFormation: Permite provisionar infraestrutura como código, automatizando o gerenciamento de recursos em contas e regiões
.
Híbrido e Borda (Edge and Hybrid)
AWS Outposts: Estende a infraestrutura e serviços nativos da AWS para virtualmente qualquer datacenter ou instalação local
.
AWS Wavelength: Otimizado para aplicações de computação de borda móvel, entregando baixa latência em redes 5G
.
AWS Local Zones: Coloca computação, armazenamento e outros serviços mais próximos dos usuários finais para aplicações sensíveis à latência
.

[MINIGUIA DE ESTUDO]
Prompt para Estudo
"Atue como um professor de certificação para AWS Cloud CErtification e monte um guia prátipo de estudos, passo a passo"

Prompt para um Guia Rápido
"Me traga os serviços AWS em uma lista de tópicos e um resumo de no máximo 2 linhas o recurso"
