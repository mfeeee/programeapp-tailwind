# Página de Planos ProgrameApp

Este repositório contém o código-fonte da página de preços e planos da **ProgrameApp**. Ela foi desenvolvida com HTML puro e estilizada usando **Tailwind CSS**.

---

## 📋 Sobre o Projeto

A página apresenta uma interface simples e intuitiva para que os usuários possam visualizar e comparar os diferentes planos de assinatura da ProgrameApp: **Básico**, **Pro**, **Enterprise** e **Master**. Cada card de plano detalha seus benefícios específicos, destacando os diferenciais para atender às diversas necessidades, desde usuários iniciantes até grandes corporações.

O design é limpo, utiliza uma paleta de cores consistente e aproveita ao máximo as classes utilitárias do Tailwind CSS.

---

## ✨ Funcionalidades Principais

* **Header Fixo:** Um cabeçalho que permanece visível no topo da página, contendo o logo e links de navegação essenciais.
* **Seção de Planos Clara:** Uma área dedicada que organiza visualmente os diferentes planos de assinatura.
* **Cards de Planos Detalhados:** Cada plano é apresentado em um card individual, incluindo:
    * Título e um breve subtítulo descritivo.
    * Lista de benefícios.
    * Preço mensal do plano.
    * Botão de chamada para contratação.
* **Estilização Tailwind CSS:** Utilização de classes utilitárias para garantir um layout consistente, cores, tipografia, espaçamento e efeitos de interação (como `hover`).

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Para a estrutura semântica e conteúdo da página.
* **Tailwind CSS:** Framework CSS utilitário para a estilização rápida e responsiva.
* **SVG:** Para os ícones de verificação dos benefícios.

---

## ⚙️ Como Configurar e Rodar o Projeto

Para visualizar e trabalhar com este projeto, você precisará configurar o ambiente Tailwind CSS.

### Pré-requisitos

Certifique-se de ter o **Node.js** e o **npm** (ou Yarn) instalados em sua máquina.

### Passos para Instalação e Configuração

1.  **Clone o Repositório:**
    Abra seu terminal e execute:
    ```bash
    git clone https://github.com/mfeeee/programeapp-tailwind.git
    cd programeapp-tailwind
    ```

2.  **Inicialize o Projeto Node.js e Instale o Tailwind CSS:**
    No diretório raiz do projeto, execute os seguintes comandos:
    ```bash
    npm install tailwindcss @tailwindcss/cli   # Instala o Tailwind CSS como dependência de desenvolvimento
    ```

3.  **Compile o CSS do Tailwind:**
    Agora, você pode compilar o CSS. Execute este comando no terminal:
    ```bash
    npx tailwindcss -i ./input.css -o ./output.css --watch
    ```
    * `npx tailwindcss`: Executa o comando do Tailwind CSS.
    * `-i ./input.css`: Define o arquivo de entrada (`input.css`).
    * `-o ./output.css`: Define o arquivo de saída (`output.css`), que é o CSS final e otimizado com todas as classes do Tailwind que você usou.
    * `--watch`: **Crucial para o desenvolvimento!** Este flag faz com que o Tailwind observe qualquer alteração nos seus arquivos HTML (ou outros configurados em `tailwind.config.js`) e recompile o `output.css` automaticamente cada vez que você salvar. Mantenha este comando rodando em um terminal separado enquanto você desenvolve.

6.  **Visualize o Projeto no Navegador:**
    Com o comando `--watch` rodando, basta abrir o arquivo `Nosso Planos.html` diretamente no seu navegador web. As classes Tailwind aplicadas no HTML serão renderizadas e atualizadas em tempo real.

---

## 🤝 Contribuição

Contribuições são sempre bem-vindas! Se você tiver sugestões de melhoria, encontrar algum bug ou quiser adicionar novas funcionalidades, sinta-se à vontade para:

1.  Abrir uma [Issue](https://github.com/mfeeee/programeapp-tailwind/issues) para discutir a mudança.
2.  Criar um [Pull Request](https://github.com/mfeeee/programeapp-tailwind/pulls) com suas alterações.

---

## 📄 Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE). Sinta-se à vontade para usá-lo e modificá-lo conforme suas necessidades.

---