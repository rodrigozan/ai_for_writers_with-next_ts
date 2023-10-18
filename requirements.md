# Desenvolvimento do produto

## Requisitos do sistema

Para uma aplicação de rede social destinada a escritores de literatura de fantasia, é importante definir os requisitos para atender às necessidades específicas dos usuários. Aqui estão os principais requisitos para essa aplicação:

1. **Registro de Usuário:**
   - Os usuários devem poder criar contas, fornecendo informações pessoais e detalhes sobre seu trabalho como escritores.

2. **Perfil de Usuário:**
   - Cada usuário deve ter um perfil que inclui informações sobre suas preferências de literatura de fantasia, projetos em andamento e conquistas.

3. **Planejamento de Histórias:**
   - Os usuários devem ter a capacidade de criar projetos individuais para suas histórias, onde possam planejar enredos, worldbuilding e personagens.

4. **Criação de Personagens:**
   - Uma funcionalidade para criar, editar e armazenar informações sobre personagens, incluindo nome, características, histórico e relacionamentos.

5. **Worldbuilding:**
   - Os usuários devem poder criar e organizar informações sobre os mundos imaginários em que suas histórias se passam, incluindo geografia, história, raças e culturas.

6. **Planejamento de Enredos:**
   - Uma ferramenta para esboçar a estrutura da história, incluindo capítulos, eventos-chave e conflitos.

7. **Escrita Colaborativa:**
   - Recursos para permitir que os usuários convidem outros escritores para colaborar em seus projetos, se desejarem.

8. **Escrita de Cenas e Capítulos:**
   - Um editor de texto integrado para escrever e editar cenas e capítulos, com funcionalidades básicas de formatação de texto.

9. **Integração com a API da OpenAI:**
   - Conexão com a API da OpenAI para fornecer assistência e insights durante o planejamento e escrita, como sugestões de texto, geração automática de ideias e correção gramatical.

10. **Comentários e Feedback:**
    - Capacidade de receber feedback de outros escritores e fornecer comentários sobre o trabalho deles.

11. **Fóruns e Comunidade:**
    - Criação de fóruns ou grupos de discussão temáticos para promover interação e colaboração entre os usuários.

12. **Notificações e Atualizações:**
    - Um sistema de notificações para informar os escritores sobre atividades relevantes, como comentários, convites para colaboração e atualizações de projetos.

13. **Privacidade e Segurança:**
    - Garantir a privacidade dos projetos dos usuários e fornecer opções de visibilidade pública ou privada.

14. **Acesso Móvel:**
    - Desenvolvimento de aplicativos móveis ou um site responsivo para acessar a plataforma em dispositivos móveis.

15. **Monetização Opcional:**
    - Oferecer opções de assinatura premium com recursos adicionais, como armazenamento extra ou acesso prioritário à API da OpenAI.

16. **Suporte ao Cliente:**
    - Disponibilizar suporte técnico para auxiliar os usuários com problemas ou dúvidas.

17. **Analytics e Estatísticas:**
    - Fornecer estatísticas e insights sobre o progresso dos projetos, o tempo de escrita e o uso da API da OpenAI.

Esses requisitos podem servir como base para o desenvolvimento de uma aplicação de rede social voltada para escritores de literatura de fantasia, ajudando-os a planejar, criar e compartilhar suas histórias com eficiência e criatividade.

## Análise de Requisitors

A análise de requisitos é uma etapa crítica no desenvolvimento de qualquer aplicação. Com base nos requisitos definidos para a aplicação de rede social para escritores de literatura de fantasia, podemos realizar uma análise mais detalhada:

1. **Registro de Usuário:**
   - Os usuários devem fornecer informações pessoais, como nome, e-mail e senha para criar uma conta.
   - Deve haver verificação de e-mail para garantir a autenticidade dos usuários.

2. **Perfil de Usuário:**
   - Os perfis dos usuários devem conter campos para informações pessoais, preferências literárias e um local para exibir suas conquistas como escritores.
   - Deve ser possível fazer edições no perfil, incluindo atualizações de conquistas e informações pessoais.

3. **Planejamento de Histórias:**
   - Os usuários devem poder criar projetos individuais para suas histórias, com a capacidade de fornecer títulos e descrições.

4. **Criação de Personagens:**
   - Para personagens, os campos relevantes devem incluir nome, idade, gênero, descrição física, história de fundo e relacionamentos com outros personagens.

5. **Worldbuilding:**
   - Os usuários devem poder adicionar informações sobre o mundo da história, como geografia, história, raças e culturas.

6. **Planejamento de Enredos:**
   - Os enredos devem ser organizados em capítulos e eventos-chave, com a capacidade de adicionar descrições e notas.

7. **Escrita Colaborativa:**
   - Os usuários devem poder convidar outros escritores para colaborar em projetos, definindo permissões de edição.

8. **Escrita de Cenas e Capítulos:**
   - O editor de texto deve suportar formatação básica, como negrito, itálico e listas.
   - Deve ser possível salvar automaticamente o trabalho em andamento.

9. **Integração com a API da OpenAI:**
   - A integração com a API da OpenAI deve permitir a geração de sugestões de texto e correção gramatical.
   - Os resultados da API devem ser exibidos no editor de texto de forma clara.

10. **Comentários e Feedback:**
    - Os usuários devem poder adicionar comentários a cenas, capítulos e outros elementos dos projetos.
    - Deve haver notificações para informar os escritores sobre novos comentários.

11. **Fóruns e Comunidade:**
    - Os fóruns devem ser organizados por tópicos relacionados à literatura de fantasia.
    - Os usuários podem criar tópicos de discussão e responder a outros tópicos.

12. **Notificações e Atualizações:**
    - As notificações devem incluir informações sobre atividades em projetos, respostas a comentários e convites para colaboração.

13. **Privacidade e Segurança:**
    - Os projetos podem ser configurados como públicos, privados ou acessíveis apenas para convidados.
    - Deve haver medidas de segurança para proteger dados pessoais e informações de projeto.

14. **Acesso Móvel:**
    - A aplicação deve ser acessível em dispositivos móveis, com uma interface amigável para telas menores.

15. **Monetização Opcional:**
    - Os planos de assinatura premium devem ser claramente definidos, com benefícios específicos para os assinantes.

16. **Suporte ao Cliente:**
    - Deve haver um sistema de suporte para atender às dúvidas e problemas dos usuários de forma eficaz.

17. **Analytics e Estatísticas:**
    - A aplicação deve rastrear estatísticas de uso, como o tempo gasto em projetos e a frequência de uso da API da OpenAI.

Essa análise de requisitos é fundamental para garantir que a aplicação atenda às necessidades dos escritores de literatura de fantasia, oferecendo uma plataforma eficiente para planejar, criar e compartilhar suas histórias, bem como acessar recursos da API da OpenAI para aprimorar sua escrita.

## Arquitetura de Software

Para projetar a arquitetura do software que utiliza Next.js com TypeScript e um banco de dados MySQL, considerando os requisitos definidos, é fundamental criar uma estrutura de banco de dados que acomode as informações de perfil de usuário, preferências literárias, projetos e conexões com outros escritores. Aqui está uma visão geral da estrutura de banco de dados:

### Tabelas do Banco de Dados:

1. **Tabela de Usuários:**
   - Armazena informações pessoais dos usuários, como nome, e-mail, senha (criptografada) e informações de contato.

2. **Tabela de Perfis de Usuário:**
   - Contém campos para informações adicionais do perfil do usuário, como descrição, foto de perfil e conquistas como escritor.

3. **Tabela de Preferências Literárias:**
   - Registra as preferências literárias do usuário, como gêneros de fantasia preferidos e autores favoritos.

4. **Tabela de Livros:**
   - Permite aos usuários listar os livros que escreveram ou estão em andamento, com detalhes como título, sinopse e data de publicação.

5. **Tabela de Worldbuildings:**
   - Armazena informações sobre os mundos imaginários criados pelos escritores, incluindo detalhes geográficos, históricos e culturais.

6. **Tabela de Personagens:**
   - Registra informações sobre personagens, como nome, idade, gênero, descrição física e relacionamentos com outros personagens.

7. **Tabela de Plots:**
   - Permite que os escritores planejem enredos, capítulos e eventos-chave em suas histórias.

8. **Tabela de Conexões:**
   - Mantém o controle das conexões entre escritores na plataforma, permitindo seguir e ser seguido.

### Relacionamentos do Banco de Dados:

- A tabela de Usuários se relaciona com a tabela de Perfis de Usuário através de uma chave estrangeira, associando cada perfil a um usuário.
- A tabela de Usuários também se relaciona com as tabelas de Preferências Literárias, Livros, Worldbuildings, Personagens, Plots e Conexões, permitindo que cada usuário adicione, edite e acesse suas informações nessas tabelas.
- As tabelas de Worldbuildings e Personagens podem estar relacionadas aos Projetos (por exemplo, cada Worldbuilding ou Personagem pode estar associado a um Projeto específico se o escritor desejar).

### API Backend:

- O backend, desenvolvido em Node.js (usando TypeScript), será responsável por fornecer as APIs necessárias para interagir com o banco de dados.
- As rotas e controladores devem ser implementados para criar, recuperar, atualizar e excluir informações nas tabelas do banco de dados.
- A integração com a API da OpenAI pode ser implementada no backend para fornecer sugestões e correções de texto durante o planejamento e escrita.

### Frontend Next.js:

- O frontend deve ser construído com Next.js e TypeScript, oferecendo uma experiência de usuário amigável.
- As páginas e componentes devem ser projetados para permitir que os usuários gerenciem seus perfis, projetos, conexões e outras informações.
- Integre formulários para entrada de dados do usuário, como informações pessoais, preferências literárias, detalhes de projetos e conexões com outros escritores.
- Implemente um editor de texto para escrita de cenas e capítulos, com integração da API da OpenAI para assistência.

Essa arquitetura fornece uma base sólida para a aplicação, permitindo aos escritores de literatura de fantasia criar, planejar e compartilhar suas histórias, além de se conectar com outros membros da plataforma. Certifique-se de implementar medidas de segurança adequadas, como autenticação e autorização, para proteger os dados dos usuários.

### Scripts para criação das tabelas:

Aqui estão os scripts para criar as tabelas no MySQL, incluindo as relações entre elas:

```sql
-- Tabela de Usuários
CREATE TABLE Usuarios (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(255) NOT NULL,
    email VARCHAR(255) NOT NULL UNIQUE,
    senha VARCHAR(255) NOT NULL,
    informacoes_contato TEXT
);

-- Tabela de Perfis de Usuário
CREATE TABLE PerfisUsuario (
    id INT AUTO_INCREMENT PRIMARY KEY,
    descricao TEXT,
    foto_perfil VARCHAR(255),
    conquistas_escritor TEXT,
    usuario_id INT,
    FOREIGN KEY (usuario_id) REFERENCES Usuarios(id)
);

-- Tabela de Preferências Literárias
CREATE TABLE PreferenciasLiterarias (
    id INT AUTO_INCREMENT PRIMARY KEY,
    generos_preferidos TEXT,
    autores_favoritos TEXT,
    livros_favoritos TEXT,
    usuario_id INT,
    FOREIGN KEY (usuario_id) REFERENCES Usuarios(id)
);

-- Tabela de Series (opcional)
CREATE TABLE Series (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(255) NOT NULL,
    descricao TEXT,
    usuario_id INT,
    FOREIGN KEY (usuario_id) REFERENCES Usuarios(id)
);

-- Tabela de Livros
CREATE TABLE Livros (
    id INT AUTO_INCREMENT PRIMARY KEY,
    titulo VARCHAR(255) NOT NULL,
    sinopse TEXT,
    data_publicacao DATE,
    serie_id INT, -- Chave estrangeira para Series (opcional)
    usuario_id INT,
    FOREIGN KEY (usuario_id) REFERENCES Usuarios(id),
    FOREIGN KEY (serie_id) REFERENCES Series(id)
);

-- Tabela de Capitulos
CREATE TABLE Capitulos (
    id INT AUTO_INCREMENT PRIMARY KEY,
    titulo VARCHAR(255) NOT NULL,
    numero INT,
    livro_id INT, -- Chave estrangeira para Livros
    usuario_id INT,
    FOREIGN KEY (livro_id) REFERENCES Livros(id),
    FOREIGN KEY (usuario_id) REFERENCES Usuarios(id)
);

-- Tabela de Cenas
CREATE TABLE Cenas (
    id INT AUTO_INCREMENT PRIMARY KEY,
    titulo VARCHAR(255) NOT NULL,
    descricao TEXT,
    capitulo_id INT, -- Chave estrangeira para Capitulos
    usuario_id INT,
    FOREIGN KEY (capitulo_id) REFERENCES Capitulos(id),
    FOREIGN KEY (usuario_id) REFERENCES Usuarios(id)
);

-- Tabela de Projetos
CREATE TABLE Projetos (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(255) NOT NULL,
    descricao TEXT,
    usuario_id INT,
    FOREIGN KEY (usuario_id) REFERENCES Usuarios(id)
);


-- Tabela de Worldbuildings
CREATE TABLE Worldbuildings (
    id INT AUTO_INCREMENT PRIMARY KEY,
    detalhes_geograficos TEXT,
    detalhes_historicos TEXT,
    detalhes_culturais TEXT,
    usuario_id INT,
    projeto_id INT, -- Se relaciona com projetos
    FOREIGN KEY (usuario_id) REFERENCES Usuarios(id),
    FOREIGN KEY (projeto_id) REFERENCES Projetos(id)
);

-- Tabela de Personagens
CREATE TABLE Personagens (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nome VARCHAR(255) NOT NULL,
    idade INT,
    genero VARCHAR(255),
    descricao_fisica TEXT,
    relacionamentos TEXT,
    usuario_id INT,
    projeto_id INT, -- Se relaciona com projetos
    FOREIGN KEY (usuario_id) REFERENCES Usuarios(id),
    FOREIGN KEY (projeto_id) REFERENCES Projetos(id)
);

-- Tabela de Plots
CREATE TABLE Plots (
    id INT AUTO_INCREMENT PRIMARY KEY,
    descricao TEXT,
    capitulo INT,
    evento_chave BOOLEAN,
    usuario_id INT,
    projeto_id INT, -- Se relaciona com projetos
    FOREIGN KEY (usuario_id) REFERENCES Usuarios(id),
    FOREIGN KEY (projeto_id) REFERENCES Projetos(id)
);

-- Tabela de Conexões
CREATE TABLE Conexoes (
    id INT AUTO_INCREMENT PRIMARY KEY,
    seguidor_id INT,
    seguido_id INT,
    FOREIGN KEY (seguidor_id) REFERENCES Usuarios(id),
    FOREIGN KEY (seguido_id) REFERENCES Usuarios(id)
);
```

Esses scripts criam as tabelas e estabelecem as relações necessárias para atender aos requisitos da aplicação. Certifique-se de ajustar o tamanho dos campos e tipos de dados conforme necessário para suas necessidades específicas. Além disso, é importante implementar as restrições de chave estrangeira (FOREIGN KEY) para manter a integridade dos dados.