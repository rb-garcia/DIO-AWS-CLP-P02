# DIO-AWS-CLP-P02
Desafio de Projeto AWS - A Importância da Segurança

# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA

Data: 26/06/2023
Empresa: Abstergo Industries 
Responsável: Ricardo Barrionuevo Garcia

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Ricardo Barrionuevo Garcia. O objetivo do projeto foi elencar 3 medidas de segurança em conjunto dos serviços da AWS, com a finalidade de aumentar a segurança na empresa.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 medidas de segurança. A seguir, serão descritas as etapas da implementação:

Medida 1: 
- Gerenciamento de acessos: a ferramenta disponibilizada pela AWS para o gerenciamento de acesso é a IAM (Identity and Access Management) que permite o gerenciamento detalhado de
acessos e identidades. Através da ferramenta IAM pode ser feito o gerenciamento dos usuários, grupos, politicas e roles do cliente. Permite definir também quais as politicas serão
utilizadas para a criação de senhas de usuários.


Medida 2: 
- Criptografia: a implantação de criptografia protege as informações por meio do uso de algoritmos codificados, hashes e assinaturas. Permite a proteção, tanto de dados em repouso
(dados em volume EBS, em buckets S3, ...) como em trânsito (dados sendo enviados de uma origem para um destino). A ferramenta AWS Key Management Service disponibilizada permite o
gerenciamento das chaves de criptografia utilizada para o controle de acesso e autorizações. 


Medida 3: 
- Verificações de Segurança Automatizadas: a AWS Security Hub automatiza as verificações de segurança e a detecção de ameaças. Centraliza os alertas de segurança. Enquanto O AWS GuardDuty protege
as contas da AWS com detecção inteligente de ameaças o AWS Inspector fornece gerenciamento automatizado e continuo de vulnerabilidades em escala.


## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado melhorar sua capacidade de atender aos principais requisitos de segurança e conformidade, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

AWS IAM
https://aws.amazon.com/pt/iam/

Criptografia AWS
https://aws.amazon.com/pt/what-is/cryptography/

AWS Key Management Service
https://aws.amazon.com/pt/kms/

AWS Key Security Hub
https://aws.amazon.com/pt/security-hub/features/

AWS GuardDuty
https://docs.aws.amazon.com/guardduty/index.html

AWS Inspector
https://docs.aws.amazon.com/inspector/index.html


Assinatura do Responsável pelo Projeto:

Ricardo Barrionuevo Garcia
