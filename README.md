# 💰 Análise Financeira em R

Projeto desenvolvido em R e RStudio para análise de receitas, despesas e lucros utilizando estatística descritiva e visualização de dados.

---

## 🎯 Objetivo

Analisar dados financeiros mensais e gerar indicadores que auxiliem na tomada de decisão.

---

## 🚀 Tecnologias Utilizadas

- R
- RStudio
- Git
- GitHub

---

## 📋 Dados Utilizados

```r
meses <- c("Jan", "Fev", "Mar", "Abr", "Mai", "Jun")

receitas <- c(2000, 2500, 2200, 3000, 2800, 3500)

despesas <- c(1200, 1400, 1300, 1800, 1600, 2000)
```

---

## 📊 Cálculo do Lucro

```r
lucro <- receitas - despesas
```

Resultado:

```text
800 1100 900 1200 1200 1500
```

---

## 📈 Estatísticas Financeiras

### Receita Média

```r
mean(receitas)
```

Resultado:

```text
2666.67
```

### Receita Total

```r
sum(receitas)
```

Resultado:

```text
16000
```

### Despesa Total

```r
sum(despesas)
```

Resultado:

```text
9300
```

### Lucro Total

```r
sum(lucro)
```

Resultado:

```text
6700
```

---

## 📊 Tabela Financeira

```r
dados <- data.frame(
  meses,
  receitas,
  despesas,
  lucro
)

print(dados)
```

---

## 📉 Gráfico de Receitas

```r
barplot(
  receitas,
  names.arg = meses,
  col = "green",
  main = "Receitas Mensais",
  ylab = "R$"
)
```

---

## 📉 Gráfico de Despesas

```r
barplot(
  despesas,
  names.arg = meses,
  col = "red",
  main = "Despesas Mensais",
  ylab = "R$"
)
```

---

## 📈 Gráfico de Lucro

```r
plot(
  lucro,
  type = "o",
  col = "blue",
  main = "Lucro Mensal",
  xlab = "Meses",
  ylab = "Lucro"
)
```

---

## 💻 Código Principal

```r
meses <- c("Jan", "Fev", "Mar", "Abr", "Mai", "Jun")

receitas <- c(2000, 2500, 2200, 3000, 2800, 3500)

despesas <- c(1200, 1400, 1300, 1800, 1600, 2000)

lucro <- receitas - despesas

dados <- data.frame(
  meses,
  receitas,
  despesas,
  lucro
)

print(dados)

mean(receitas)
sum(receitas)
sum(despesas)
sum(lucro)

barplot(receitas,
        names.arg = meses,
        col = "green")

plot(lucro,
     type = "o",
     col = "blue")
```

---

## 📚 Conceitos Aprendidos

- Vetores
- Data Frames
- Análise Financeira
- Estatística Descritiva
- Receita Total
- Despesa Total
- Lucro
- Visualização de Dados
- Git e GitHub

---

## 🎓 Conclusão

Este projeto demonstra como utilizar a linguagem R para analisar dados financeiros, calcular métricas importantes e criar visualizações que facilitam a interpretação dos resultados.

---

## 👤 Autor

**Maris**

Projeto desenvolvido durante os estudos de Análise de Dados com R e RStudio.

📍 Curitiba - PR, Brasil

---

⭐ Se gostou do projeto, deixe uma estrela no repositório.
