# 🧠 Simulado AWS Certified Solutions Architect – Professional  
50 Perguntas e Respostas com toggle interativo

Este material foi criado para facilitar o estudo da certificação **AWS Certified Solutions Architect – Professional**, utilizando um formato interativo para treinar perguntas e visualizar as respostas sob demanda.

---

## 📋 Perguntas e Respostas

<details>
<summary><strong>1. O que é o AWS Well-Architected Framework e quais são seus cinco pilares?</strong></summary>

O AWS Well-Architected Framework ajuda a avaliar arquiteturas e implementá-las de acordo com melhores práticas. Seus pilares são: Excelência operacional, Segurança, Confiabilidade, Eficiência de desempenho, Otimização de custos.

</details>

<details>
<summary><strong>2. Explique como o AWS Global Infrastructure é organizado em regiões, zonas de disponibilidade e edge locations.</strong></summary>

Regiões são áreas geográficas separadas. Cada região contém Zonas de Disponibilidade (AZs), que são datacenters fisicamente isolados. Edge Locations são locais otimizados para cache e entrega de conteúdo com serviços como CloudFront e Route 53.

</details>

<details>
<summary><strong>3. Quais são as diferenças entre AWS Organizations, AWS Control Tower e AWS Landing Zone?</strong></summary>

AWS Organizations: gestão de múltiplas contas com políticas (SCP). Control Tower: facilita a criação de landing zones com boas práticas. Landing Zone: arquitetura inicial segura com múltiplas contas, redes e políticas.

</details>

<details>
<summary><strong>4. Como funcionam Service Control Policies (SCP) e qual seu impacto em contas filhas?</strong></summary>

SCPs definem permissões máximas para contas da organização. Mesmo que um IAM permita uma ação, ela será bloqueada se a SCP negar.

</details>

<details>
<summary><strong>5. Quando e por que usar AWS Resource Access Manager (RAM)?</strong></summary>

Usa-se o RAM para compartilhar recursos entre contas sem duplicá-los, como subnets, VPCs, etc. Ideal em ambientes multi-conta.

</details>

<details>
<summary><strong>6. Detalhe o uso de AWS CloudFormation e AWS CDK para infraestrutura como código.</strong></summary>

CloudFormation: define recursos com YAML/JSON. CDK: usa linguagens como TypeScript, Python para gerar templates CloudFormation.

</details>

<details>
<summary><strong>7. Como implementar pipelines CI/CD com AWS CodePipeline, CodeBuild e CodeDeploy?</strong></summary>

CodePipeline orquestra o fluxo. CodeBuild compila e testa. CodeDeploy realiza o deploy em EC2, ECS, Lambda.

</details>

<details>
<summary><strong>8. Explique a diferença entre Elastic Load Balancer clássico, Application Load Balancer e Network Load Balancer.</strong></summary>

CLB: legado. ALB: L7 (HTTP/HTTPS), roteamento baseado em path/host. NLB: L4 (TCP/UDP), alta performance e IP fixo.

</details>

<details>
<summary><strong>9. Como projetar uma arquitetura de alta disponibilidade e tolerância a falhas para instâncias EC2?</strong></summary>

Use Auto Scaling, Load Balancer entre múltiplas AZs, snapshots e instâncias em standby.

</details>

<details>
<summary><strong>10. Quais são os mecanismos de auto scaling em EC2, ECS e DynamoDB?</strong></summary>

EC2: Auto Scaling Groups. ECS: Service Auto Scaling. DynamoDB: Auto Scaling por throughput ou on-demand.

</details>

---
