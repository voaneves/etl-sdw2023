<a id="top"></a>

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/voaneves/etl-sdw2023/main/assets/logo/logo-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/voaneves/etl-sdw2023/main/assets/logo/logo-light.svg" />
  <img alt="etl-sdw2023 logo: the monogram Et" src="https://raw.githubusercontent.com/voaneves/etl-sdw2023/main/assets/logo/logo-light.svg" width="112" height="112" />
</picture>

<h1>etl-sdw2023</h1>

<p>
  <strong>Generates personalized investment messages for bank customers using generative AI.</strong><br />
  <sub>Python ETL notebook for the Santander Dev Week 2023</sub>
</p>

<p>
  <a href="https://voaneves.github.io/etl-sdw2023/"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/voaneves/etl-sdw2023/main/assets/buttons/landing-dark.svg" /><img alt="View landing page" src="https://raw.githubusercontent.com/voaneves/etl-sdw2023/main/assets/buttons/landing-light.svg" height="40" /></picture></a>
  <a href="https://colab.research.google.com/github/voaneves/etl-sdw2023/blob/main/Personaliza%C3%A7%C3%A3o_de_Engajamento_de_Clientes_no_Santander_usando_IA_Generativa.ipynb"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/voaneves/etl-sdw2023/main/assets/buttons/colab-dark.svg" /><img alt="Open in Colab" src="https://raw.githubusercontent.com/voaneves/etl-sdw2023/main/assets/buttons/colab-light.svg" height="40" /></picture></a>
</p>

<p><sub>Need something like this? <a href="https://voaneves.com/en/#contact"><strong>Let's talk →</strong></a></sub></p>

<p>
  <a href="https://github.com/voaneves/etl-sdw2023/blob/main/LICENSE"><img src="https://img.shields.io/github/license/voaneves/etl-sdw2023?style=flat-square&color=0A0A0A" alt="MIT License" /></a>
  <img src="https://img.shields.io/badge/Python-Pandas-b80000?style=flat-square" alt="Python and Pandas" />
  <a href="https://github.com/voaneves/etl-sdw2023/issues"><img src="https://img.shields.io/github/issues/voaneves/etl-sdw2023?style=flat-square&color=0A0A0A" alt="Open issues" /></a>
</p>

<p>
  <a href="#about-the-project">About</a> ·
  <a href="#technologies-used">Technologies</a> ·
  <a href="#features">Features</a> ·
  <a href="#getting-started">Getting started</a> ·
  <a href="#contact">Contact</a>
</p>

</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/voaneves/etl-sdw2023/main/assets/brand/rule-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/voaneves/etl-sdw2023/main/assets/brand/rule-light.svg" />
  <img alt="" src="https://raw.githubusercontent.com/voaneves/etl-sdw2023/main/assets/brand/rule-light.svg" width="100%" />
</picture>

## About the project

Este projeto gera mensagens de investimento personalizadas para clientes de um banco a partir dos dados de cada um, usando IA generativa.

Foi desenvolvido como parte das iniciativas da Santander Dev Week 2023 e visa a implementação de um pipeline ETL eficaz para personalizar mensagens de marketing para clientes do Santander usando IA generativa. Utilizando dados dos clientes e a API do Google Bard, nosso objetivo é gerar mensagens que não apenas capturam a essência das necessidades e comportamentos financeiros individuais, mas também enfatizam a importância de tomar decisões de investimento informadas.

Abaixo é um exemplo de output:

> **Resposta baseada em regras:**
>
> Olá Devweekerson,
> Iniciar o investimento com um orçamento apertado é um desafio, mas não
> impossível.
> Com seu limite de cartão mais elevado, você tem a liberdade de explorar uma
> variedade de investimentos.Investir é a chave para multiplicar seu dinheiro.
> Não deixe sua grana parada! Vamos investir?
>
> **Mensagem do Bard:**
>
> Olá Devweekerson,
>
> Vi que você tem um saldo de R$ 624,12 e um limite de crédito de R$ 2.000,00.
> Isso é um bom começo, mas você pode fazer mais para melhorar sua situação
> financeira.
>
> Os investimentos são uma ótima forma de fazer seu dinheiro crescer. Eles
> podem ajudá-lo a alcançar seus objetivos financeiros, como comprar uma casa,
> viajar ou se aposentar.
>
> Existem muitos tipos de investimentos diferentes, por isso é importante fazer
> sua pesquisa e encontrar o que é certo para você. Eu posso ajudá-lo com isso.
>
> Entre em contato comigo para agendar uma consulta.
>
> Atenciosamente,
> Banqueiro expert

O fluxo de trabalho é composto por várias etapas de ETL (Extração, Transformação e Carregamento), incluindo:

1. Extração de dados dos clientes a partir de uma API
2. Geração de mensagens personalizadas usando IA Generativa
3. Exibição dessas mensagens de uma forma que seja tanto atraente quanto informativa

A implementação é feita em Python, utilizando várias bibliotecas e APIs para realizar as tarefas necessárias.

### Technologies Used

The project uses the following technologies:

- Python
- Pandas
- Requests
- Google Bard API
- Santander Dev Week 2023 API (Swagger UI)

Built for the **Santander Bootcamp 2023 (Data Science with Python)**.

## Features

This project includes the following features:

- Extração de IDs de usuários de uma planilha CSV
- Geração de mensagens de marketing personalizadas usando IA Generativa (Google Bard)
- Exibição dessas mensagens de forma atraente e informativa
- Possibilidade de integração com outros APIs através do requests

## Getting started

1. Clone this repository:

   ```bash
   git clone https://github.com/voaneves/etl-sdw2023.git
   ```

2. Read the results without running anything in the
   [notebook on GitHub](https://github.com/voaneves/etl-sdw2023/blob/main/Personaliza%C3%A7%C3%A3o_de_Engajamento_de_Clientes_no_Santander_usando_IA_Generativa.ipynb).
3. Or [open it in Colab](https://colab.research.google.com/github/voaneves/etl-sdw2023/blob/main/Personaliza%C3%A7%C3%A3o_de_Engajamento_de_Clientes_no_Santander_usando_IA_Generativa.ipynb) and upload
   [`SDW2023.csv`](https://github.com/voaneves/etl-sdw2023/blob/main/SDW2023.csv).

## To do

- [ ] Integração com outras APIs de IA
- [ ] Melhorias na interface do usuário

## Reporting bugs

1. Check whether the bug is already in [Issues](https://github.com/voaneves/etl-sdw2023/issues).
2. If not, open a new issue with a clear title and the steps to reproduce it.
3. If possible, include screenshots or the notebook cell that fails.

Pull requests are welcome.

## Contact

<p>
  <a href="https://voaneves.com/en/#contact"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/voaneves/etl-sdw2023/main/assets/buttons/hire-dark.svg" /><img alt="Let's talk" src="https://raw.githubusercontent.com/voaneves/etl-sdw2023/main/assets/buttons/hire-light.svg" height="40" /></picture></a>
  <a href="https://voaneves.com/en/"><picture><source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/voaneves/etl-sdw2023/main/assets/buttons/site-dark.svg" /><img alt="voaneves.com" src="https://raw.githubusercontent.com/voaneves/etl-sdw2023/main/assets/buttons/site-light.svg" height="40" /></picture></a>
</p>

<a href="https://linkedin.com/in/voaneves">LinkedIn</a> · <a href="mailto:victorneves478@gmail.com">E-mail</a>

<p align="center">
  <img alt="VOANEVES mark" src="https://raw.githubusercontent.com/voaneves/etl-sdw2023/main/assets/brand/mark-duo.svg" width="32" height="32" />
</p>

<p align="center"><sub>Released under the <a href="https://github.com/voaneves/etl-sdw2023/blob/main/LICENSE">MIT License</a>.</sub></p>

<p align="center"><sub><a href="#top">↑ Back to top</a></sub></p>
