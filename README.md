# Pet-Sisters
# 🐾 PetConnect - Adote um Amigo!

O PetConnect é um sistema moderno de adoção de animais, desenvolvido para simplificar o processo de encontrar um lar amoroso para cães e gatos resgatados. Utiliza uma interface amigável baseada em Tailwind CSS e JavaScript puro (ES6) para oferecer uma experiência de usuário rápida e interativa.

### ✨ Principais Funcionalidades

| Funcionalidade | Descrição | Implementação |
| :--- | :--- | :--- |
| **Catálogo Interativo** | Exibe todos os pets disponíveis em uma grade de cards responsiva. | `MOCK_PETS` (dados), `renderPets()` |
| **Filtros e Busca** | Permite filtrar por tipo de animal (Cães/Gatos/Todos) e buscar em tempo real por nome ou raça. | `setCategory()`, `renderPets()`, `state` |
| **Detalhes do Pet** | Exibe informações completas (idade, raça, descrição, traços) ao clicar no card, com transição de tela. | `openPetDetail()`, `closePetDetail()` |
| **Sistema de Modais** | Pop-ups para ações como Adotar, Doar, Voluntariar e simulação de Match com IA. | `openModal()`, `closeModal()` |
| **Navegação Suave** | Links no cabeçalho utilizam *scroll* suave para seções (Hero, Pets, Histórias, Doações). | `handleNavigate()` |
| **Design Moderno** | Utiliza Tailwind CSS com tema de cores personalizado (laranja e preto) e ícones Lucide. | `tailwind.config`, classes CSS |

### 🛠️ Estrutura do Projeto

| Arquivo | Descrição |
| :--- | :--- |
| **`index.html`** | Estrutura da página, links para CSS/JS, configuração do Tailwind (CDN) e a lógica de layout. |
| **`style.css`** | Estilos globais (fundo, `fade-in`, scrollbar). |
| **`script.js`** | Lógica de aplicação: dados (`MOCK_PETS`), manipulação do DOM, filtros, modais e gerenciamento de estado. |

### 🚀 Como Executar

1.  Certifique-se de ter os três arquivos (`index.html`, `style.css`, `script.js`) no mesmo diretório.
2.  Abra o arquivo **`index.html`** no seu navegador de preferência.
