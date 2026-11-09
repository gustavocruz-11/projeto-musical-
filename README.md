# 🎵 Sistema Musical — Interface Web (Sprint 1)

Este repositório contém a interface frontend do **Sistema Musical**, desenvolvida em HTML5 e CSS3 puro. O sistema é composto por telas de autenticação, navegação principal, gestão de artistas, gestão de músicas e consulta à biblioteca musical.

---

## 📌 Sobre o Projeto

O **Sistema Musical** é uma aplicação web projetada para o gerenciamento de catálogos musicais. Nesta primeira fase (Sprint 1), a interface foi construída com foco na estruturação semântica, acessibilidade, responsividade e componentes visuais padronizados através de variáveis CSS.

---

## 🚀 Funcionalidades da Interface

- 🔑 **Página de Autenticação (`login.html`)**: Formato de cartão centralizado com suporte a acessibilidade (`autocomplete`) e bloco informativo de credenciais de teste.
- 🎛️ **Painel de Controle (`index.html`)**: Menu principal em grade (*grid layout*) interativa para navegação rápida entre os módulos do sistema.
- 🎤 **Gestão de Artistas (`cadastro_artista.html`)**:
  - Formulário estruturado em grade para cadastro de artistas, gêneros, países e foto de perfil (`multipart/form-data`).
  - Tabela explicativa de artistas cadastrados com botões de ação para edição, exclusão e atalho direto para vinculação de músicas.
- 🎵 **Gestão de Músicas (`cadastro_musica.html`)**:
  - Formulário completo para cadastro de faixas, integração de link do YouTube, upload de capa de álbum e campo estendido para letras de música.
  - Tabela com pré-visualização de capas e reprodução de vídeos.
- 🎼 **Biblioteca Musical (`listagem_musicas.html`)**:
  - Área de filtros (busca geral, artista e gênero).
  - Tabela completa de dados de faixas com suporte a atalhos de reprodução externa (`target="_blank"`).

---

## 📁 Estrutura de Arquivos

```text
.
├── index.html               # Painel principal / Menu do sistema
├── login.html               # Tela de autenticação de usuário
├── cadastro_artista.html    # Formulário e listagem de artistas
├── cadastro_musica.html     # Formulário e listagem de faixas
├── listagem_musicas.html    # Biblioteca musical com painel de filtros
└── styles.css               # Folha de estilos centralizada e responsiva
