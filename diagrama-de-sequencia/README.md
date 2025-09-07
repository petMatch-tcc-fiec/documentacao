# Documentação de Diagramas de Sequência
Este repositório contém os diagramas de sequência UML (Unified Modeling Language) que documentam os principais fluxos de interação do sistema de adoção de animais. Esses diagramas são ferramentas essenciais para entender a comunicação entre as diferentes partes da aplicação (Usuário/ONG, Interface, Back-end e Banco de Dados).

Os diagramas foram criados usando o PlantUML, uma linguagem simples de texto que gera diagramas visuais.

## Diagramas de Sequência Incluídos
**1. Cadastro de Usuário**

Este diagrama detalha o processo de cadastro de um novo usuário ou ONG na plataforma, incluindo a verificação de e-mail e os caminhos de sucesso e erro.

**2. Login de Usuário**

Representa o fluxo de autenticação de usuários, mostrando a validação das credenciais e os cenários de login bem-sucedido e malsucedido.

**3. Cadastro de Animal (pela ONG)**

Descreve como uma ONG cadastra um novo animal para adoção, desde a inserção dos dados na interface até o registro no banco de dados.

**4. Visualização de Listas (pela ONG)**

Ilustra o processo pelo qual uma ONG acessa e visualiza a lista de animais disponíveis e as filas de interessados em adoção.

**5. Manifestação de Interesse em Animal (pelo Usuário)**

Mostra como um usuário expressa interesse em um animal, sendo adicionado à fila de espera para adoção.

**6. Aprovação de Adoção (pela ONG)**

Detalha o fluxo de aprovação de um usuário para a adoção, que marca o animal como "adotado" no sistema.

## Como Utilizar
O código-fonte PlantUML para gerar esses diagramas está documentado separadamente, permitindo que você os edite ou reproduza facilmente.

Para visualizar, editar ou gerar os diagramas a partir do código, você pode usar ferramentas como:

**PlantUML Online Server:** Cole o código e gere o diagrama instantaneamente.

**Extensões para IDEs** (como Visual Studio Code ou IntelliJ) que suportam PlantUML.
