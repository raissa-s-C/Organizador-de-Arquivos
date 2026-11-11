# Organizador de Arquivos com Python

Uma ferramenta de automação simples e eficiente desenvolvida em Python para organizar arquivos de qualquer pasta de forma automática, economizando tempo e mantendo o seu computador arrumado.

---

## Funcionalidades

- **Seleção Dinâmica:** Abre uma interface gráfica intuitiva para o usuário selecionar a pasta desejada.
- **Organização Inteligente:** Identifica automaticamente a extensão de cada arquivo e os move para subpastas categorizadas (ex: `imagens/`, `planilhas/`, `pdfs/`, `csv/`).
- **Criação Automática:** Cria as pastas de destino necessárias dinamicamente caso elas ainda não existam no diretório.

---

## Tecnologias Utilizadas

- **Linguagem:** Python
- **Bibliotecas Nativas:** 
  - `os` (manipulação de caminhos e arquivos do sistema)
  - `tkinter` (interface gráfica e pop-up de seleção de diretório)

---

## Como Usar

1. Certifique-se de que você tem o Python instalado no seu computador.
2. Clone este repositório ou baixe o arquivo do projeto.
3. Abra o terminal na pasta do projeto e execute o script:
   ```bash
   python main.py
