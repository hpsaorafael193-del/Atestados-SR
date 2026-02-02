# Gerador de Atestados Médicos – Hospital São Rafael

Sistema web para geração de atestados médicos em formato digital, com layout institucional, validações básicas e exportação do documento em imagem (PNG).

O projeto foi desenvolvido como **site único**, porém estruturado com padrões de organização e separação de responsabilidades, simulando o comportamento de um módulo real de um sistema clínico maior.

---

## ✨ Funcionalidades

- Geração de atestados por tipo:
  - Comparecimento
  - Afastamento
  - Restrição de atividade
  - Retorno ao trabalho
  - Escolar
- Layout em **formato cartão**, adequado para documentos curtos
- Rodapé fixo contendo:
  - Nome do médico
  - CRM
  - Assinatura digital
- Campo de observações com:
  - Limite de caracteres
  - Limite visual de **3 linhas**
  - Suporte a quebra de linha (Enter)
- Marca d’água institucional
- Preview em tempo real
- Upload e remoção de assinatura
- Exportação do atestado em PNG
- Funcionamento totalmente front-end (sem backend)

---

## 🧱 Estrutura do Projeto

/
├── index.html
└── assets/
├── css/
│ └── style.css
├── js/
│ └── script.js
└── logo/
└── fundo.png


---

## 🛠️ Tecnologias Utilizadas

- HTML5
- CSS3 (Flexbox e layout fixo)
- JavaScript (Vanilla JS)
- html2canvas (exportação de imagem)

---

## 🎯 Objetivo do Projeto

Este projeto foi desenvolvido para fins de **estudo, prática e demonstração técnica**, sendo utilizado no contexto de **Roleplay (RP)** pelo grupo **Hospital São Rafael (HP)**, exclusivamente no servidor **Eldorado**.

O sistema **não possui finalidade médica real** e não deve ser utilizado em ambientes clínicos ou profissionais reais.

---

## ▶️ Como Executar

1. Clone ou baixe este repositório
2. Abra o projeto utilizando um servidor local (ex: Live Server no VS Code)
3. Acesse o arquivo `index.html` pelo navegador
4. Preencha os dados e gere o atestado

> ⚠️ A exportação do documento funciona corretamente quando o projeto é executado via `http://localhost`.

---

## 📌 Avisos Importantes

- Este sistema **não armazena dados**
- Não há integração com banco de dados ou APIs
- Todas as informações inseridas são fictícias
- O documento gerado não possui validade médica ou legal

---

## 🔒 Licença de Uso

Este projeto **NÃO é open-source**.

O uso do sistema é **restrito ao autor** e aos **membros autorizados do grupo Hospital São Rafael (HP)**, exclusivamente no servidor **Eldorado (RP)**.

A visualização do código é permitida para fins de avaliação técnica e portfólio, porém **é proibida a redistribuição, reutilização ou uso comercial**.

Consulte o arquivo `LICENSE` para mais detalhes.

---

## 👤 Autor

Desenvolvido por **Luidhy C. dos Santos**

Projeto criado para fins educacionais, prática de desenvolvimento front-end e uso interno em Roleplay (RP).
