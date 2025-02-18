# Distribuidora de Jogos

## Escopo do Sistema
O sistema "Distribuidora de Jogos" é projetado para facilitar o cadastro, gerenciamento e distribuição de jogos desenvolvidos por estúdios e desenvolvedores independentes. O objetivo é fornecer uma plataforma que permita o registro e a distribuição de jogos, além da visualização dos ganhos obtidos com cada título. O sistema inclui funcionalidades para cadastro e login de usuários (desenvolvedores e estúdios), gerenciamento de pessoas envolvidas no desenvolvimento, cadastro de jogos com detalhes específicos, visualização de ganhos e relatórios detalhados.

**Funcionalidades Principais**:

1. **Tela de Cadastro e Login de Usuários**
- Os usuários são os desenvolvedores e estúdios de desenvolvimento. É de responsabilidade deles cadastrar os jogos e também as pessoas que participam no desenvolvimento desses jogos.
- Para cadastro do usuário guardamos o seguinte:
   - Nome
   - Email
   - Senha
   - CNPJ/CPF
   - Dados Bancários

2. **Tela de Cadastro de Pessoas**
- Todo usuário do sistema pode cadastrar uma pessoa se ela ainda não estiver no banco. As pessoas assumem papel no desenvolvimento dos jogos. Guardamos as seguintes informações:
   - Nome
   - Email
   - CPF
   - Rede Social
   - Telefone

3. **Cadastro de Jogos**
- Código de barras (ou SKU) deve ser único por jogo.
- Um jogo pode ser um título único ou parte de uma série/franquia. Cada jogo deve conter as seguintes informações:
   - Título do Jogo
   - Plataforma (PC, console, mobile)
   - Gênero
   - Data de Lançamento
   - ISRC (International Standard Recording Code) único
   - Informações sobre desenvolvedores, designers, artistas, etc.

4. **Visualização dos Ganhos Recebidos por Jogo**
- Relatórios detalhados sobre os ganhos recebidos por cada jogo ou franquia, incluindo estatísticas de vendas e receitas.

5. **Capacidade de Deletar**
- Possibilidade de deletar registros de jogos e pessoas cadastradas, com as devidas verificações de segurança para evitar exclusões acidentais.

## Membros da Equipe e Papel
-**Gessica Teixeira Bomfim** - *Full-Stack Developer* - [GitHub Gessica](https://github.com/gessicatb)

-**Alexssander Fernandes Candido** - *Backend Developer* [GitHub Alexssander](https://github.com/JuBinLuB)

-**Gabriel Abreu Miller Godoi** - *Full-stack Developer* - [GitHub Gabriel Miller](https://github.com/gabrielgmiller)

-**Gabriel Henrique Silva** - *Backend Developer* - [GitHub Gabriel Henrique](https://github.com/gabrielhs33)

## Tecnologias
- **Linguagem de Programação**: Python
- **Banco de Dados**: PostgreSQL
## Backlogs

### Backlog do Produto
1. **História do Usuário**: Como desenvolvedor ou estúdio, quero cadastrar novos usuários para gerenciar jogos e pessoas associadas.
2. **História do Usuário**: Como desenvolvedor ou estúdio, quero adicionar pessoas ao sistema com informações detalhadas para atribuí-las aos jogos.
3. **História do Usuário**: Como desenvolvedor ou estúdio, quero cadastrar novos jogos com informações completas para disponibilizá-los na plataforma.
4. **História do Usuário**: Como desenvolvedor ou estúdio, quero visualizar relatórios de ganhos por jogo para analisar o desempenho financeiro.
5. **História do Usuário**: Como desenvolvedor ou estúdio, quero deletar registros de jogos e pessoas quando necessário para manter o sistema atualizado.
6. **História do Usuário**: Como desenvolvedor ou estúdio, quero receber notificações sobre novas vendas e atualizações importantes para estar sempre informado.
7. **História do Usuário**: Como desenvolvedor ou estúdio, quero realizar pesquisas avançadas de jogos e pessoas para encontrar informações específicas rapidamente.
8. **História do Usuário**: Como desenvolvedor ou estúdio, quero integrar o sistema com plataformas de vendas para sincronizar automaticamente vendas e ganhos.
9. **História do Usuário**: Como desenvolvedor ou estúdio, quero que o sistema tenha autenticação e autorização seguras para proteger os dados sensíveis.
10. **História do Usuário**: Como desenvolvedor ou estúdio, quero um sistema de suporte ao cliente para resolver dúvidas e problemas rapidamente.

### Backlog da Sprint
1. **História do Usuário**: Como desenvolvedor ou estúdio, quero cadastrar novos usuários.
- **Tarefas**:
     - Implementar a funcionalidade de cadastro de usuários.
     - Desenvolver a interface de usuário para cadastro e login.
     - Configurar a persistência de dados dos usuários no banco de dados.

2. **História do Usuário**: Como desenvolvedor ou estúdio, quero adicionar novas pessoas ao sistema.
- **Tarefas**:
     - Implementar a funcionalidade de cadastro de pessoas.
     - Desenvolver a interface para adicionar e gerenciar informações de pessoas.
     - Configurar a persistência de dados das pessoas no banco de dados.

3. **História do Usuário**: Como desenvolvedor ou estúdio, quero cadastrar novos jogos.
- **Tarefas**:
     - Implementar a funcionalidade de cadastro de jogos.
     - Desenvolver a interface para inserir e editar informações dos jogos.
     - Configurar a persistência de dados dos jogos no banco de dados.

4. **História do Usuário**: Como desenvolvedor ou estúdio, quero visualizar os ganhos recebidos por jogo.
- **Tarefas**:
     - Desenvolver a tela para visualização de ganhos por jogo.
     - Implementar relatórios detalhados de vendas e receitas.
     - Integrar com o backend para fornecer dados atualizados.

5. **História do Usuário**: Como desenvolvedor ou estúdio, quero receber notificações sobre novas vendas e atualizações importantes.
- **Tarefas**:
    - Implementar o sistema de notificações.
    - Desenvolver a interface para exibir notificações.
    - Configurar regras e gatilhos para envio de notificações.

# Diagramas UML
- **Diagrama de Classes**:
<div align="center">
   <img src="https://github.com/user-attachments/assets/2af8af97-d4ea-4975-aff8-c383dd149823" alt="Imagem1" width="720"/>
   <br/>
   <em>Figura 1: Diagrama de Classes</em>
</div>

<br/><br/>

- **Diagrama de Atividades**:
<div align="center">
   <img src="https://github.com/user-attachments/assets/5544492e-a027-4451-bb4a-d892caa37a56" alt="Imagem2" width="720"/>
   <br/>
   <em>Figura 2: Diagrama de Atividades para cadastro de pessoa</em>
</div>

<br/><br/>

<div align="center">
   <img src="https://raw.githubusercontent.com/gessicatb/Trabalho-Eng-de-Software/refs/heads/main/diagrama%20de%20atividades/Delete%20Product%20Activity%20Diagram0.png" alt="Imagem3" width="720"/>
   <br/>
   <em>Figura 3: Diagrama de Atividades para deletar produto</em>
</div>
 
# Protótipo de Interface
Link do protótipo: https://www.figma.com/design/KKrtFos5nfhSKV3wNS561z/LevelUP?node-id=0-1&t=qyWs8kaNPpC4PP9Z-1

