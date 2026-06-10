# 📊 Calculadora de Assiduidade para Gincanas

Uma calculadora simples, bonita e justa para contabilizar a presença das equipes em atividades de gincanas, eventos, treinamentos ou competições.

---

## 🎯 Objetivo

Garantir uma pontuação justa entre equipes de tamanhos diferentes.

Exemplo:

| Equipe   | Membros |
| -------- | ------: |
| Azul     |      30 |
| Amarelo  |      25 |
| Verde    |      20 |
| Vermelho |      15 |

Sem um cálculo proporcional, equipes menores poderiam ser beneficiadas ou prejudicadas.

A calculadora resolve isso automaticamente.

---

## ⚖️ Como funciona

A pontuação é calculada com base no percentual de presença da equipe.

### Fórmula

```text
Pontos = (Presentes ÷ Total de Membros) × Pontuação Máxima
```

O resultado é arredondado para um número inteiro.

```javascript
Math.round((presentes / total) * maximo)
```

---

## 📈 Exemplo de Equipes

| Equipe   | Membros |
| -------- | ------: |
| Azul     |      30 |
| Amarelo  |      25 |
| Verde    |      20 |
| Vermelho |      15 |

---

## 📊 Exemplo de Cálculo

Supondo que a atividade valha 100 pontos:

| Equipe   | Total | Presentes | Pontuação |
| -------- | ----: | --------: | --------: |
| Azul     |    24 |        30 |        80 |
| Amarelo  |    20 |        25 |        80 |
| Verde    |    16 |        20 |        80 |
| Vermelho |    12 |        15 |        80 |

Neste exemplo, todas as equipes tiveram **80% de presença**, portanto todas receberam **80 pontos**, independentemente do número de integrantes.

Isso demonstra que o sistema é proporcional e não favorece equipes maiores ou menores.

---

## ✅ Por que é justo?

A calculadora utiliza o percentual de presença.

Isso significa que:

* Equipe com 15 membros e 15 presentes = 100 pontos
* Equipe com 30 membros e 30 presentes = 100 pontos

Ambas alcançaram 100% de presença.

Da mesma forma:

* 12 de 15 presentes = 80 pontos
* 24 de 30 presentes = 80 pontos

Como ambas tiveram 80% de presença, recebem exatamente a mesma pontuação.

Nenhuma equipe recebe vantagem por possuir mais ou menos integrantes.

---

## 🚀 Recursos

* Cálculo automático de assiduidade
* Pontuação proporcional
* Arredondamento sem casas decimais
* Validação de dados
* Interface moderna e responsiva
* Funciona em celular, tablet e computador
* Tema visual inspirado nas equipes da gincana:

  * 🔵 Azul
  * 🔴 Vermelho
  * 🟢 Verde
  * 🟡 Amarelo

---

## 🖥️ Como usar

1. Abra o arquivo HTML em qualquer navegador.
2. Informe:

   * Total de membros da equipe
   * Quantidade de presentes
   * Pontuação máxima da atividade
3. Clique em **Calcular Pontuação**.
4. O sistema exibirá:

   * Pontuação obtida
   * Percentual de presença

---

## 📱 Compatibilidade

Funciona em:

* Google Chrome
* Microsoft Edge
* Mozilla Firefox
* Safari
* Navegadores mobile Android
* Navegadores mobile iPhone

---

## 💡 Sugestões futuras

* Cadastro de múltiplas equipes
* Ranking automático
* Histórico de atividades
* Exportação para Excel
* Exportação para PDF
* Painel administrativo
* Aplicativo Android e iOS
* Dashboard de classificação geral

---

## 🏆 Resultado

A Calculadora de Assiduidade garante que o desempenho das equipes seja medido pela participação proporcional dos seus integrantes, mantendo a competição equilibrada, transparente e justa para todos os envolvidos.

---

## 📄 Licença

Projeto livre para utilização em gincanas, igrejas, escolas, empresas e eventos comunitários.

Desenvolvido para promover uma competição justa baseada na participação e assiduidade dos membros das equipes. 🏅
