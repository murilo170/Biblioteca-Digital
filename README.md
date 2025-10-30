# 🏛️ Sistema de Gerenciamento de Biblioteca (Java - CLI)

Este projeto simula um sistema básico de controle de acervo de biblioteca, rodando totalmente no terminal (Command Line Interface - CLI). Foi desenvolvido em Java com foco total na aplicação dos conceitos de **Orientação a Objetos (POO)** e no uso eficiente de estruturas de dados (`Collections`).

É um projeto ideal para demonstrar o domínio de Java sem depender de interfaces gráficas complexas.

## 🎯 Foco e Conceitos em Destaque

| Conceito de Java | Aplicação no Projeto |
| :--- | :--- |
| **POO Avançada** | Uso de classes (`Livro`, `GerenciadorBiblioteca`) e encapsulamento (`private` + Getters/Setters). |
| **Collections** | Utilização do `ArrayList` para armazenar e gerenciar a lista de objetos `Livro` (o acervo). |
| **Separ. de Responsabilidades** | A lógica de dados está isolada na classe `GerenciadorBiblioteca`, enquanto a classe `Main` cuida apenas da interação com o usuário. |
| **Boas Práticas** | Uso de constantes (ex: `STATUS_DISPONIVEL`) e método `toString()` para uma saída limpa no console. |

## ✨ Funcionalidades

O sistema permite ao usuário realizar as seguintes operações via menu de console:

* **Adicionar Livro:** Cadastro de Título, Autor, ISBN e Ano.
* **Listar Livros:** Exibe todo o acervo com o status atual de cada livro.
* **Buscar Livro:** Encontra livros por Título ou Autor.
* **Emprestar/Devolver:** Altera o status do livro no acervo utilizando seu ID.

## 🛠️ Como Rodar o Projeto Localmente

O projeto exige o ambiente Java (JDK) configurado.

1.  **Clone o Repositório:**
    ```bash
    git clone [LINK_DO_SEU_REPOSITORIO]
    cd nome-do-seu-repositorio-java
    ```
2.  **Navegue para a pasta `src`:**
    ```bash
    cd src
    ```
3.  **Execute o Arquivo Principal:**
    Se estiver usando uma IDE (como VS Code ou IntelliJ), basta rodar o `Main.java`.
    No terminal (após compilar as classes, se necessário):
    ```bash
    java Main 
    ```
    O sistema iniciará e o menu de opções aparecerá no console.

---

## 👨‍💻 Autor

Este projeto foi desenvolvido por:

**Murilo Souza / @murilo107**

* **LinkedIn:** www.linkedin.com/in/murilo-souza-0a00291ab
* **GitHub:** (https://github.com/murilo170)
