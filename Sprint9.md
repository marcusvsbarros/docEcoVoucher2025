<span id="topo">

<h1 align="center">Sprint 9: 01/06/2025 a 26/06/2025</h1>

A Sprint 9 marcou a etapa final de desenvolvimento do projeto **Ecovoucher**, com foco na conclusão técnica do aplicativo mobile e na implantação completa do ecossistema (frontend, backend e banco de dados) na plataforma **Amazon Web Services (AWS)**. Esta fase foi decisiva para consolidar todas as entregas anteriores em uma solução robusta, funcional e pronta para a apresentação final, realizada no dia **26/06/2025**.

---

## 🏁 Objetivos da Sprint

- Finalizar o desenvolvimento de todas as telas do app mobile;
- Integrar completamente o frontend, backend e banco de dados;
- Implantar todo o projeto na nuvem (AWS), com foco em escalabilidade e segurança;
- Realizar testes finais de usabilidade e funcionalidade;
- Preparar versão estável para apresentação final.

---

## 🔧 Desenvolvimento Mobile

- Finalização das interfaces do app:
  - Tela de perfil e configurações
  - Tela de envio de comprovante de reciclagem (upload de imagem)
  - Tela de parceiros e utilização de cashback
- Ajustes de usabilidade e responsividade
- Aplicação da lógica completa de autenticação, requisições e estados

---

## ☁️ Implantação na AWS

Após as análises da sprint anterior, foram definidos e aplicados os seguintes serviços:

| Componente       | Serviço AWS Utilizado               |
|------------------|--------------------------------------|
| Frontend (React) | Amazon S3 + CloudFront              |
| Backend (Node.js)| Amazon EC2 + Security Groups        |
| Banco de Dados   | MongoDB Atlas com integração via VPC|
| Upload de Imagens| Amazon S3 Bucket com políticas IAM  |
| Monitoramento    | Amazon CloudWatch                   |

- Criação e configuração da **EC2 Instance** com ambiente Node.js e PM2 para rodar o backend em produção
- Deploy do frontend com **build React** no **S3** e distribuição via **CloudFront**
- Integração segura entre backend e banco via string de conexão protegida por variáveis de ambiente (.env)
- Configuração de políticas de segurança (IAM, Security Groups e controle de acessos)

---

## 🔄 Integração Final

A integração entre as três camadas (Mobile → Backend → Banco de Dados) foi testada e validada:

- Cadastro e login com autenticação funcional
- Registro de materiais recicláveis
- Atualização de saldo e cashback por usuário
- Listagem e visualização de parceiros
- Upload de imagem com retorno via URL do S3

---

## 📑 Documentação e Apresentação

- Registro completo da arquitetura do projeto na Wiki
- Diagrama de arquitetura atualizado com serviços da AWS
- Geração de manual de uso técnico e funcional do sistema
- Preparação da apresentação final com roteiro demonstrativo:
  - Visão geral do projeto
  - Fluxo completo do usuário
  - Estrutura na nuvem
  - Demonstração do app em tempo real

---

<div align="center">

![Arquitetura AWS](https://github.com/marcusvsbarros/docEcoVoucher2025/blob/main/ArquiteturaAWS.png)
</div>

---

## 🤝 Colaboração e Encerramento

A entrega desta sprint representa a consolidação de meses de trabalho colaborativo e aprendizado prático, com um projeto funcional e tecnicamente sólido. A equipe se manteve engajada até a finalização do escopo, respeitando os prazos e entregando um sistema pronto para aplicação real.

---

→ [Retornar à Página Inicial](https://github.com/marcusvsbarros/readMeTest/blob/main/README.md)
