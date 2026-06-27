# Tonal Trainer 🎸

O **Tonal Trainer** é um aplicativo web interativo, minimalista e totalmente responsivo desenvolvido para músicos e estudantes de música praticarem percepção de teoria musical, harmonia funcional, graus e campos harmônicos. 

O sistema automatiza o sorteio aleatório de cifras, graus musicais e tons naturais, funcionando como um excelente aliado para acelerar a memorização de formatos e a velocidade na troca de acordes no instrumento.

---

## 🔗 Demonstração

Você pode visualizar e testar o projeto rodando em tempo real através do link abaixo:
👉 **[Acesse o Tonal Trainer aqui](https://yurikoga.github.io/tonal-trainer/)**

---

## 🎨 Design & Identidade Visual

O projeto foi construído do zero focando em uma estética moderna, limpa e imersiva:
- **Tema Escuro (Dark Mode):** Interface baseada em tons pretos profundos e cinzas escuros para reduzir a fadiga visual durante treinos noturnos.
- **Efeito LED Glow:** Utilização de elementos de fundo dinâmicos com cores vibrantes e desfoque avançado (`filter: blur(80px)`), simulando a iluminação ambiente de um estúdio musical ou fitas LED.
- **Responsividade Mobile-First:** Todo o layout foi planejado para se adaptar perfeitamente a telas de celulares e tablets, contando com botões amplos e fáceis de tocar durante a prática com o instrumento.

## 🛠️ Módulos e Funcionalidades

O sistema conta com 4 ferramentas fundamentais de treino:
1. **Sorteador de Cifras:** Sorteia notas naturais estruturadas de A a G para treinar visualização rápida de acordes.
2. **Sorteador de Graus:** Focado na fixação dos graus musicais em algarismos romanos (I a VII) para o estudo de harmonia.
3. **Graus / Tons:** Treino duplo na mesma tela, combinando graus e tons de forma independente para desafiar o raciocínio rápido.
4. **Troca de Acorde:** Sorteador otimizado com foco nos graus pilares principais (I, IV e V) para ganho de velocidade e cadência.

## 🚀 Tecnologias Utilizadas

- **HTML5:** Estrutura semântica organizada de forma limpa e acessível.
- **CSS3:** Estilização global moderna, uso de variáveis, filtros de desfoque, efeito de vidro (*backdrop-filter*) e *media queries* para responsividade completa.
- **JavaScript (Vanilla):** Lógica nativa de geração pseudo-aleatória (`Math.random()`) para realizar os sorteios instantaneamente, sem a necessidade de bibliotecas ou frameworks externos.

---

## 📁 Estrutura de Pastas do Projeto

O projeto está organizado da seguinte forma para garantir o funcionamento correto dos caminhos relativos:

```text
harmonia-treino/
│
├── index.html                 # Menu Principal do Sistema
├── README.md                  # Documentação do Projeto (Este arquivo)
│
└── assets/
    ├── css/
    │   └── style.css          # Estilo Global Unificado (LED Glow)
    │
    └── pages/
        ├── cifra.html         # Sorteador de Cifras
        ├── grau.html          # Sorteador de Graus
        ├── grau-tom.html      # Sorteador de Graus e Tons
        └── troca-de-acorde.html # Treino de Troca de Acordes
