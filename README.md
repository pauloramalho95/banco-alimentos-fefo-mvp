# Banco de Alimentos — Gestão de Triagem e Fila FEFO (MVP)

Aplicação web mobile-first (PWA) desenvolvida para otimizar o fluxo de recebimento, triagem rápida e expedição de hortifrúti em bancos de alimentos, aplicando a regra logística **FEFO** (*First Expired, First Out* — Primeiro que Vence, Primeiro que Sai) para reduzir o desperdício biológico na doca e fortalecer a segurança alimentar (**ODS 2 — Fome Zero e Agricultura Sustentável**).

---

## 🎯 Problema e Objetivo

Em operações de doca de bancos de alimentos, itens perecíveis correm risco constante de perda por falta de ordenação visual cronológica de validade. Este MVP resolve essa dor fornecendo aos operadores uma interface simples, acessível e direta para:
1. Cadastrar novos lotes na chegada da carga.
2. Identificar visualmente os lotes mais críticos por prazo de validade.
3. Realizar a baixa de estoque na saída para cozinhas comunitárias.

---

## 📱 Telas e Fluxos do MVP

* **Tela 1 — Entrada e Triagem Rápida:** Formulário de doca com validação de dados para cadastrar novo lote (alimento, peso em kg, validade e origem).
* **Tela 2 — Execução Central (Fila FEFO):** Listagem automática de lotes ativos ordenada pelo menor prazo de validade, com sinalização multimodal de criticidade (vermelho/amarelo/verde com ícones e texto descritivo).
* **Tela 3 — Baixa, Alertas e Resultados:** Janela de registro de baixa (doação vs. descarte), conferência de peso e exibição de métricas do dia (quilos expedidos e taxa de aproveitamento).

---

## ♿ Acessibilidade e Ergonomia (WCAG 2.1 AA)

* **Multimodalidade de Estado:** A urgência de cada lote não depende exclusivamente de cor; combina cor, texto explicativo por extenso e símbolos geométricos (`⚠️`, `⏳`, `✓`).
* **Área de Toque Ergonômica:** Botões com altura mínima de 48px e espaçamento adequado para operadores que utilizam luvas ou operam em ambiente de armazém.
* **Alto Contraste:** Textos e números estruturados com contraste superior a 4,5:1 sobre o fundo.

---

## 🛠️ Tecnologias Previstas

* **Front-end:** HTML5 semântico, CSS3 responsivo e JavaScript (PWA).
* **Back-end / Dados:** Python / Banco de Dados relacional (PostgreSQL).
* **Versionamento:** Git e GitHub com boas práticas de commits semânticos.

---

## 🚀 Como Visualizar o Projeto

Por se tratar do repositório inicial da solução e documentação do MVP, os protótipos de interface e os arquivos de código-fonte estão organizados na pasta principal deste repositório.

*Status do Projeto: MVP em fase de validação operacional.*
