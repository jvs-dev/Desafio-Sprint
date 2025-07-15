# 🚗 Calculadora de Gastos com Combustível Ford

Este projeto é uma **Calculadora de Gastos com Combustível**, desenvolvida como parte de um desafio do projeto Ford Enter, com o objetivo de auxiliar usuários a gerenciar seus custos de transporte diários.

A aplicação permite calcular o consumo de combustível necessário para o trajeto casa-trabalho, registrar preços de postos e exibir estatísticas como o menor valor pesquisado, a média dos preços e o gasto diário.

---

## 🌟 Funcionalidades

- **Cálculo de Consumo Necessário:** Insira a distância diária (ida e volta) entre sua casa e o trabalho e o consumo médio do seu veículo para saber quantos litros de combustível você precisa.
- **Registro de Preços de Combustível:** Adicione os preços de combustível de diferentes postos que você pesquisou.
- **Análise de Preços:** Visualize o menor preço de combustível registrado e a média de todos os preços.
- **Custo Diário Estimado:** Calcule seu gasto diário com combustível com base no menor preço registrado.
- **Armazenamento Local:** Todos os dados são salvos no armazenamento local do navegador.
- **Tema Personalizável:** Alternância entre tema claro e escuro.
- **Documentação Interativa:** Documentação interna explicativa com opção de leitura por voz.
- **Limpeza de Dados:** Botão para apagar todos os dados salvos.

---

## 🚀 Como Usar

1. Abra o arquivo `index.html` no seu navegador.

2. **Informe a Distância:**
   - Preencha o campo “DISTÂNCIA DA SUA CASA ATÉ SEU TRABALHO” (em km).

3. **Informe o Consumo:**
   - Digite o consumo médio do veículo (em km/L).

4. **Consumo Necessário:**
   - O valor será atualizado automaticamente para ida e volta.

5. **Registre Preços de Combustível:**
   - Preencha o campo “VALOR DO COMBUSTÍVEL PESQUISADO” e clique em “REGISTRAR”. (máx: 10 registros)

6. **Acompanhe os Gastos:**
   - Veja o menor valor, média e gasto diário calculado automaticamente.

7. **Deletar Postos:**
   - Clique no “X” vermelho ao lado do posto registrado.

8. **Mudar Tema:**
   - Clique no ícone de sol/lua no canto superior direito.

9. **Documentação da Solução:**
   - Clique no ícone de livro para abrir a explicação do projeto e ativar leitura por voz.

10. **Apagar Dados Salvos:**
    - Clique no ícone de lixeira no canto superior direito.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estrutura da página.
- **CSS3:** Estilização e responsividade.
- **JavaScript:** Lógica, DOM, `localStorage` e funcionalidades interativas.
- **Google Fonts:** Fonte "Poppins" e ícones "Material Icons".
- **Bootstrap Icons:** Ícones visuais e funcionais.
- **Ionicons:** Ícones adicionais personalizados.

---

## ⚙️ Estrutura do Código

O projeto está contido em um único arquivo `index.html`, conforme permitido no desafio.

### Destaques do JavaScript:

- **Seletores & Variáveis:** Utilização do `getElementById` para manipulação dos elementos.
- **localStorage:** Persistência de dados como distância, consumo, tema e preços.
- **Funções de Cálculo:**
  - `calculateRequiredFuel()`
  - `updateLowestPrice()`
  - `updateMediumPrice()`
  - `updateDailyCost()`
- **Manipulação de DOM:** Postos adicionados dinamicamente à lista.
- **Validação e Alertas:** Função `createMessage()` exibe mensagens visuais ao usuário.
- **Recursos Visuais:** Tela de carregamento, modal com documentação e leitura por voz com `SpeechSynthesisUtterance`.

---

## 🎯 Desafio Proposto (Contexto)

Projeto criado como resposta a um desafio de Inglês Técnico e Lógica de Programação da **Ford**, com os seguintes objetivos:

- Calcular o consumo necessário em litros.
- Identificar o local mais acessível para abastecimento.
- Calcular a média dos preços pesquisados.
- Estimar o gasto diário com combustível.

Embora o desafio original sugerisse o uso de `prompt` e `parseFloat`, foi adotada uma abordagem mais amigável ao usuário com inputs HTML, garantindo robustez na entrada de dados e evitando `NaN`.

---

## 👨‍💻 Autor

Feito com ❤️ por [jvs-dev](https://github.com/jvs-dev)
