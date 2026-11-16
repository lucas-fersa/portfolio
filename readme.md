# 💼 Portfólio Profissional — Lucas Fersa.dev

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![ETEC](https://img.shields.io/badge/ETEC-Desenvolvimento_de_Sistemas-red?style=for-the-badge)

> **Autor:** Lucas Fersa  
> **Instituição:** ETEC — Técnico em Desenvolvimento de Sistemas  
> **Objetivo:** Apresentar minha trajetória acadêmica, habilidades técnicas e projetos desenvolvidos na área de tecnologia.

---

## 📌 Sobre o Projeto

O **Portfólio Profissional** é um site responsivo desenvolvido como atividade prática no curso de **Desenvolvimento de Sistemas da ETEC**. 

O projeto tem como objetivo centralizar minha apresentação profissional e acadêmica, exibindo minhas principais competências em programação, ferramentas de desenvolvimento e os projetos criados ao longo do primeiro semestre do curso.

---

## 🚀 Tecnologias e Recursos Utilizados

Para construir uma interface moderna, acessível e responsiva, foram aplicadas as seguintes tecnologias:

* 🏗️ **HTML5 Semântico:** Organização do conteúdo em seções claras (`<nav>`, `<section>`, `<footer>`), hierarquia adequada de títulos (`<h1>`) e navegação interna suave por âncoras.
* 🎨 **CSS3 Customizado:** Paleta de cores própria (azul, verde-azulado e âmbar), variáveis de tema para modo claro/escuro, animações leves de entrada e efeitos de elevação nos cards.
* 🅱️ **Bootstrap 5:** Sistema de Grid responsivo, barra de navegação fixa (`navbar sticky-top`) com Scrollspy, carrossel interativo (`carousel-fade`), cards e componentes estilizados.
* ⚡ **JavaScript:** Controle de alternância entre **Modo Claro e Modo Escuro** (com preferência salva no navegador via `localStorage`) e botão dinâmico para voltar ao topo.
* 🎯 **Devicon:** Biblioteca de ícones vetoriais para representar visualmente as tecnologias dominadas (HTML5, CSS3, Bootstrap, Python, GitHub e VS Code).

---

## 🧩 Estrutura do Portfólio

O site está organizado nas seguintes seções principais:

| Seção | Descrição |
| :--- | :--- |
| 🧭 **Barra de Navegação** | Menu responsivo fixo no topo (`sticky-top`) com destaque ativo (Scrollspy) e alternador de tema Claro/Escuro. |
| 🖼️ **Carrossel de Destaque** | Banner rotativo em tela cheia (`carousel-fade`) com carregamento otimizado e botão de ação *"Ver projetos"*. |
| 👨‍💻 **Perfil & Formação** | Apresentação profissional, linha do tempo da formação acadêmica (ETEC e Univesp), seção de currículo com link para o LinkedIn e stack de ferramentas. |
| 📂 **Vitrine de Projetos** | Cards interativos com elevação ao passar o mouse e links diretos para projetos práticos (incluindo o *Sistema de Monitoramento de Reservatório de Água em Python*). |
| 📬 **Contato** | Links diretos para E-mail, GitHub e LinkedIn para conexões profissionais. |

---

## ✨ Melhorias Realizadas no Código

Em relação à primeira versão, o portfólio passou por uma etapa de refatoração, correções técnicas e aprimoramentos de design:

* 🛠️ **Correções Técnicas e de Funcionamento:**
  * Ajuste no botão do menu mobile (correção dos atributos `data-bs-toggle` e `data-bs-target`).
  * Correção de classes digitadas incorretamente (`align-items-center`), remoção de CSS duplicado no carrossel e definição das classes `profile-img` e `project-img`.
  * Inclusão de espaços adequados entre atributos HTML e adição de `rel="noopener noreferrer"` nos links externos para maior segurança.
* ♿ **Acessibilidade, SEO e Desempenho:**
  * Adição de título principal `<h1>` na página e rótulos de acessibilidade (`aria-label`).
  * Remoção do `lazy loading` no primeiro banner do carrossel para acelerar o carregamento inicial da página.
  * Atualização da descrição do projeto em Python para refletir fielmente sua função: o **monitoramento de um reservatório de água**.
* 🎨 **Conteúdo, Design e Experiência do Usuário (UX):**
  * Criação de uma **linha do tempo de formação acadêmica**, seção de **currículo com link para o LinkedIn** e ajuste do posicionamento para *"Estudante de Desenvolvimento de Sistemas e IA"*.
  * Implementação de **paleta de cores própria** (azul, verde-azulado e âmbar) substituindo o padrão do Bootstrap, além de **modo claro/escuro** persistente no navegador.
  * Adição de rolagem suave, destaque do item ativo no menu (**Scrollspy**), botão para voltar ao topo, animações leves de entrada e efeito de elevação nos cards.
* 🤖 **Revisão Assistida:** As alterações técnicas foram realizadas com o auxílio do **Claude Sonnet 5.5** por meio da ferramenta **Perplexity**, que revisou o código, apontou falhas e sugeriu boas práticas de acessibilidade e desempenho, cabendo a mim todas as decisões finais de conteúdo e design.

---

## 📁 Estrutura de Pastas

Para que todas as imagens do carrossel, foto de perfil e capas dos projetos carreguem corretamente, o projeto segue esta organização:

```text
portfolio-profissional/
│
├── index.html                  # Estrutura principal da página e estilos internos
├── README.md                   # Documentação do projeto
└── imagens/                    # Diretório de imagens e banners
    ├── slide1.png
    ├── slide2.png
    ├── slide3.png
    ├── perfil.jpg
    ├── lucaskart.png
    ├── programapy.png
    └── siteetec.png
```

---

## 🖥️ Como Visualizar o Projeto

Como o projeto utiliza apenas tecnologias front-end estáticas e bibliotecas via CDN (Bootstrap e Devicon), basta seguir os passos abaixo:

1. **Clone ou baixe este repositório:**
   ```bash
   git clone https://github.com/lucas-fersa/seu-repositorio.git
   ```
2. **Acesse a pasta do projeto.**
3. **Abra o arquivo `index.html`** diretamente no seu navegador (Google Chrome, Edge, Firefox, etc.) com conexão à internet para carregar os estilos do Bootstrap e os ícones do Devicon.

---

⭐ *Desenvolvido por **Lucas Fersa** durante o curso Técnico em Desenvolvimento de Sistemas — ETEC.*