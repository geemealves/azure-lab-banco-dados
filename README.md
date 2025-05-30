# Lab Azure - Instância de Banco de Dados

Este repositório foi criado como parte do desafio proposto no curso **Microsoft +50 anos: Computação em Nuvem com Azure**, oferecido pela [DIO](https://dio.me).

O objetivo foi praticar o processo de criação e configuração de uma **instância de Banco de Dados** na plataforma Microsoft Azure, além de documentar a experiência com anotações e dicas úteis.

---

## 📘 O que foi aprendido

### ☁️ Conceitos de Banco de Dados na Nuvem
- Diferença entre bancos de dados locais (on-premise) e gerenciados na nuvem.
- Vantagens de usar o Azure SQL Database: alta disponibilidade, backup automático, escalabilidade e segurança.

### 🛠️ Criação de Instância de Banco de Dados no Azure
Passos realizados:
1. Acesse o portal: [https://portal.azure.com](https://portal.azure.com)
2. Selecione **"SQL databases"** > **"Create"**
3. Configure os campos:
   - **Resource Group:** selecione ou crie um novo
   - **Database name**
   - **Server:** criar novo servidor SQL
     - Nome do servidor
     - Login e senha de administrador
     - Região
4. Escolha o tipo de recurso (Compute + Storage)
5. Configure opções de segurança e conectividade (por exemplo, regras de firewall)
6. Clique em **Review + create** e depois em **Create**

---

## 💡 Dicas e Anotações

- **Servidor SQL:** precisa ser criado antes ou durante o processo.
- **Firewall:** é necessário liberar seu IP local para se conectar com o banco usando ferramentas externas (ex: Azure Data Studio ou SQL Server Management Studio).
- **Plano gratuito:** alguns recursos podem ser usados gratuitamente por tempo limitado.
- Utilize **tags** para organizar seus recursos no portal.

---

## 📷 Capturas de Tela

Caso deseje incluir imagens, crie uma pasta `/images` e adicione prints dos seguintes momentos:
- Tela de criação do banco
- Configuração do servidor SQL
- Regra de firewall
