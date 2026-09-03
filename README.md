💰 Extrato de Contrato – Calculadora Financeira
![Status](https://img.shields.io/badge/status-ativo-brightgreen)
![Licença](https://img.shields.io/badge/licença-MIT-blue)
![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
> **Calculadora de Extrato de Contrato** – Ferramenta web para simular impostos, encargos e partilha líquida de valores contratuais, com interface limpa e responsiva.
---
📌 Sobre o Projeto
Este projeto é uma calculadora financeira que replica o formato clássico de extrato de contrato, permitindo:
Inserir o valor bruto do contrato com formatação monetária automática.
Calcular automaticamente impostos (ISS, PIS, COFINS, IRPJ, CSLL) e encargos (pró-labore, contabilidade, tarifas bancárias), com percentuais editáveis diretamente na tabela.
Visualizar subtotais, total de saídas e o valor líquido estimado.
Dividir o líquido entre quantas pessoas desejar, mostrando o valor por pessoa.
Copiar todo o extrato formatado para a área de transferência com um clique.
Tudo isso em uma única página HTML, sem dependências externas (apenas fontes e ícones via CDN).
---
🚀 Funcionalidades
✅ Edição em tempo real – altere qualquer percentual e veja os valores se atualizarem instantaneamente.
✅ Regra do piso da contabilidade – se 1,2% do bruto for menor que R$ 500,00, o valor é automaticamente ajustado para R$ 500,00 (conforme prática comum).
✅ Divisão igualitária – defina o número de pessoas e veja o valor líquido por pessoa.
✅ Cópia do extrato – botão que copia um resumo completo (impostos, encargos, totais e divisão) em formato texto puro, pronto para colar em e-mails ou planilhas.
✅ Design responsivo – adapta-se a telas de desktop, tablets e smartphones.
✅ Máscara monetária – o campo de valor bruto aceita apenas números e formata automaticamente no padrão R$ 0,00.
---
🧰 Tecnologias Utilizadas
HTML5 – estrutura semântica
CSS3 – estilização moderna com gradientes, sombras e animações suaves (variáveis CSS para fácil manutenção)
JavaScript (ES6) – toda a lógica de cálculo, manipulação do DOM e eventos
Font Awesome – ícones para melhor experiência visual
Google Fonts (Inter) – tipografia limpa e profissional
---
📥 Como Usar
Pré‑requisitos
Nenhum! Basta ter um navegador moderno (Chrome, Firefox, Edge, Safari).
Instalação e Execução
Clone este repositório:
```bash
   git clone https://github.com/seu-usuario/extrato-contrato-calculadora.git
