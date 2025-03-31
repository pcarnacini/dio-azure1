# Data Factory DIO

## Criando um SQL Database no Azure
1. Acesse o [Portal do Azure](https://portal.azure.com/).
2. Procure por **SQL Database** e clique em **Criar**.
3. Selecione ou crie um **Grupo de Recursos**.
4. Defina um nome para o banco de dados.
5. Clique em **Criar um novo servidor** e configure:
   - Nome do servidor.
   - Região.
   - Login e senha de administrador.
6. Escolha o **Plano de Preço**.
7. Clique em **Revisar + Criar** e depois **Criar**.

## Criando um SQL Server no Azure
1. No portal, procure por **SQL Server** e clique em **Criar**.
2. Forneça:
   - Nome do servidor.
   - Login de administrador.
   - Senha.
   - Região.
3. Clique em **Revisar + Criar**.

## Criando um Blob Storage e Containers
1. No portal, procure por **Armazenamento** e clique em **Criar**.
2. Escolha um **Grupo de Recursos** e defina um **Nome**.
3. Selecione a **Região** e o **Tipo de Redundância**.
4. Após a criação, acesse o **Storage Account** e crie um **Container**:
   - Vá para **Contêineres** e clique em **+ Contêiner**.
   - Defina um nome e a política de acesso.

## Configurando Linked Services no Data Factory
1. Acesse o **Azure Data Factory Studio**.
2. Vá para **Gerenciar** > **Linked Services** > **+ Novo**.
3. Escolha o tipo de serviço a conectar (SQL, Blob Storage, etc.).
4. Insira as credenciais e configurações necessárias.
5. Clique em **Criar**.

## Configurando Integration Runtimes
1. No **Azure Data Factory Studio**, vá para **Gerenciar** > **Integration Runtimes**.
2. Clique em **+ Novo**.
3. Escolha entre **Azure IR, Self-hosted IR ou Azure-SSIS IR**.
4. Configure e clique em **Criar**.

## Configuração do Git no Data Factory
1. Vá para **Gerenciar** > **Configuração do Git**.
2. Escolha **Azure DevOps Git** ou **GitHub**.
3. Insira:
   - Nome da organização/repositório.
   - Nome da branch principal.
   - Diretório raiz.
4. Clique em **Salvar**.
