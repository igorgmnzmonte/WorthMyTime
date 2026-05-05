# ⏳ WorthMyTime

![Badge Licença](https://img.shields.io/badge/License-MIT-green.svg)
![Badge HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![Badge CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Badge JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

> **Pare de gastar dinheiro. Comece a gastar o seu tempo de forma consciente.**

O **WorthMyTime** é um painel financeiro interativo que converte preços, financiamentos e assinaturas na única moeda que você não pode recuperar: **o seu tempo de vida**. Ao invés de perguntar "isso cabe no meu bolso?", a ferramenta faz você se perguntar "quantos meses da minha vida estou disposto a trabalhar por isso?".

---

## 🎯 O Problema

Muitas calculadoras financeiras mostram o impacto dos juros no seu saldo bancário, mas falham em gerar um verdadeiro choque de realidade. As pessoas têm dificuldade de visualizar o que significa pagar R$ 10.000 de juros, mas entendem perfeitamente o que significa **trabalhar 3 meses de graça para o banco**.

## ✨ Funcionalidades

O painel é dividido em módulos projetados para diferentes contextos de consumo:

* **⏱️ Calculadora Rápida:** Converta o preço de um produto avulso (como um celular ou uma roupa) em horas, dias ou meses trabalhados, baseado na sua escala (5x2, 6x1, 12x36) e salário reais.
* **🌍 Choque de Realidade Global:** Compare o seu poder de compra com o de trabalhadores em outros países. Descubra quantas vezes mais você precisa trabalhar para comprar itens globais (iPhone, PS5) em relação à média americana.
* **💳 A Armadilha da Parcela:** Simule financiamentos usando juros compostos (Tabela Price). O sistema separa o "Custo do Bem" do "Custo dos Juros", mostrando exatamente quanto tempo da sua vida você perderá pagando o banco.
* **💸 O Ralo das Assinaturas:** Cadastre suas despesas recorrentes (Netflix, Academia, Internet). O dashboard calcula o impacto somado ao longo de um ano e revela quantos dias de trabalho anuais são sugados apenas por mensalidades.

---

## 🚀 Como Executar o Projeto

O **WorthMyTime** foi construído com a filosofia *Zero Dependencies* (Zero Dependências). Ele roda puramente no lado do cliente, sem necessidade de servidores, bancos de dados ou compiladores.

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/seu-usuario/worthmytime.git](https://github.com/seu-usuario/worthmytime.git)
2. Navegue até o diretório:

   ```bash
   cd worthmytime
3. Abra o painel:
  Basta dar um duplo clique no arquivo index.html ou abri-lo diretamente em qualquer navegador moderno (Chrome, Firefox, Safari, Edge).

## 🛠️ Tecnologias Utilizadas
* **HTML5:** Estrutura semântica e acessível.

* **CSS3 (Vanilla):** Sistema de design responsivo com variáveis globais (:root), animações suaves e tipografia moderna do sistema operacional.

* **JavaScript (Vanilla):** Lógica matemática para conversão de tempo, cálculo de juros compostos (Tabela Price) e manipulação do DOM em tempo real com estados sincronizados.

## 📐 Matemática por trás da "Armadilha da Parcela"
Para garantir a precisão do custo do financiamento, o sistema utiliza a fórmula da Tabela Price (Sistema Francês de Amortização), padrão na maioria dos financiamentos:

O cálculo determina a prestação mensal fixa, multiplicando-a pelo prazo total para extrair a diferença exata entre o valor do bem e o montante pago em juros, convertendo esse saldo final em horas de trabalho do usuário.

## 🤝 Como Contribuir
Contribuições são muito bem-vindas! Se você tem ideias para novas calculadoras (ex: "Aluguel vs. Compra" ou "Custo do Deslocamento") ou quer ajudar no desenvolvimento da Extensão para Chrome:

1. Faça um Fork do projeto.

2. Crie uma nova branch com a sua feature: git checkout -b minha-nova-feature

3. Salve suas mudanças e faça o commit: git commit -m 'feat: Adiciona nova calculadora'

4. Envie para o seu repositório: git push origin minha-nova-feature

5. Abra um Pull Request.

## 📄 Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes. Você é livre para usar, modificar e distribuir.

Desenvolvido com ☕ e foco em educação financeira.
