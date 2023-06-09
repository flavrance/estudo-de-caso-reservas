# Estudo de caso de uma aplicação de reservas de acomodações
É uma arquitetura e estrutura cloud native

## Dinâmica proposta
Design de solução de aplicação de reserva online de acomodações 
Deverão ser consideradas duas funcionalidades principais: 
- Pesquisa de acomodações
- Reserva de acomodações nos destinos 

É importante considerar e descrever no desenho de solução: 

- Infraestrutura em Cloud 
- A aplicação deve estar disponível via Portal Web e Aplicativo Móvel 
- Declarar e justificar o padrão arquitetural escolhido
- Requisitos Funcionais 
- Requisitos não-funcionais (Segurança, Escalabilidade, Performance, etc) 

## A Arquitetura
![Arquitetura de Solução](https://raw.githubusercontent.com/flavrance/estudo-de-caso-reservas/main/draw.io/sistemas%20de%20reservas.drawio.png)
- Arquitetura Serverless;
- Orquestração de Container’s;
- Arquitetura de Microserviços;
- Arquitetura Hexagonal;
- Arquitetura Limpa;
- SOLID;

## Infraestrutura em Cloud
- Provedor de cloud escolhida: Amazon Web Services (AWS)
- Serviços da AWS utilizados:
-- Amazon CloudFront;
-- Amazon API Gateway;
-- AWS Lambda;
-- Amazon S3;
-- Amazon Elastic Kubernetes Service (EKS);
-- Amazon RDS;
-- Amazon Redis;
-- Amazon DynamoDB;
-- Amazon Elasticsearch Service;
-- Amazon MKS (Kafka);
-- WAF
- Alguns dos componentes não estão sendo exibidos na solução, mas foram abstraídos para melhor apresentação;
 
## Apresentação
[Download] (https://github.com/flavrance/estudo-de-caso-reservas/blob/main/apresentacao/sistema%20de%20reservas.pptx)