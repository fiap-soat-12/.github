<div align="center">

# Pós Tech FIAP - Tech Challenge - Grupo 12

![GitHub Release Date](https://img.shields.io/badge/Release%20Date-Fevereiro%202025-yellowgreen)
![](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellowgreen)
<br>
![](https://img.shields.io/badge/Version-%20v4.0.0-brightgreen)
</div>

### 👨‍💼👩‍💼‍ Autores

Este é um projeto que está em construção pelos desenvolvedores:

![](https://img.shields.io/badge/RM357321-Alexandre%20Miranda-blue)
<br>
![](https://img.shields.io/badge/RM357437-Diego%20Ceccon-blue)
<br>
![](https://img.shields.io/badge/RM357218-Jéssica%20Rodrigues%20-blue)
<br>
![](https://img.shields.io/badge/RM358002-Rodrigo%20Sartori-blue)
<br>
![](https://img.shields.io/badge/RM357991-Wilton%20Souza%20-blue)

### ⚠️ Problema

<p align="justify">Uma lanchonete em expansão enfrenta dificuldades em gerenciar pedidos de forma eficiente sem um sistema adequado, o que pode causar confusão, atrasos e insatisfação dos clientes. Pedidos complexos, como hambúrgueres personalizados, podem ser mal interpretados ou esquecidos, impactando negativamente os negócios. Para resolver esse problema, a lanchonete vai investir em um sistema de autoatendimento, permitindo que os clientes façam pedidos diretamente, sem depender de atendentes, otimizando o processo e melhorando a experiência dos clientes.</p>

## 🎥 Vídeo de apresentação

Para assistir ao vídeo de apresentação do projeto, que contém:
- A descrição detalhada do problema
- Arquitetura utilizada no projeto
- Solução de infraestrutura proposta
- Demonstração da aplicação em funcionamento

basta acessar o link: [Apresentação no Youtube](https://youtu.be/-56eM60woTE?si=9t6_p3IrzOuJmz1i)

### Repositório

Repositório que compõem a aplicação e a infraestrutura.

Ordem de execução: 
1. **[VPC](https://github.com/fiap-soat-12/tech-challenge-vpc)**: Contém os arquivos terraform de criação da VPC.
2. **[Queue](https://github.com/fiap-soat-12/tech-challenge-queue)**: Contém os arquivos terraform de criação das filas usando o SQS.
3. **[BD](https://github.com/fiap-soat-12/tech-challenge-db)**: Contém os arquivos terraform de criação dos Bancos de Dados no RDS.
4. **[K8S](https://github.com/fiap-soat-12/tech-challenge-k8s)**: Contém os arquivos terraform de criação do Cluster e Infraestrutura da aplicação.
5. **[Cook API](https://github.com/fiap-soat-12/tech-challenge-cook-api)**: Contém os arquivos terraform de criação da Cook API e do ECR da aplicação.
6. **[Order API](https://github.com/fiap-soat-12/tech-challenge-order-api)**: Contém os arquivos terraform de criação da Order API e do ECR da aplicação.
7. **[Payment API](https://github.com/fiap-soat-12/tech-challenge-payment-api)**: Contém os arquivos terraform de criação da Payment API e do ECR da aplicação.
8. **[Lambda Auth](https://github.com/fiap-soat-12/tech-challenge-lambda-auth)**: Contém os arquivos terraform de criação da Lambda Authorize.
9. **[Gateway](https://github.com/fiap-soat-12/tech-challenge-gateway)**: Contém os arquivos terraform de criação da API Gateway.
10. **[BDD](https://github.com/fiap-soat-12/tech-challenge-bdd)**: Contém os arquivos relacionados ao teste DBB da aplicação como todo.

