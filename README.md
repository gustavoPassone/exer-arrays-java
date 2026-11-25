# Exercícios de Arrays e Matrizes em Java

Projeto contendo 50 exercícios práticos em Java focados na manipulação de vetores (arrays unidimensionais) e matrizes (arrays bidimensionais).

## 📁 Estrutura do Projeto

Os arquivos estão organizados no pacote `exercicios.arrays`:

```text
src/
└── exercicios/
    └── arrays/
        ├── _1GuardandoNomes.java ... _30SistemaSimplesEstoque.java (Vetores)
        └── _31CriarMatriz2x3.java ... _50EstoquePorLoja.java (Matrizes)
```

### 📋 Conteúdo Abordado

- **Exercícios 1 a 30 (Vetores / Arrays 1D):**
  - Entrada e saída com `Scanner`.
  - Cálculos de soma, média aritmética, maior e menor valor.
  - Contagem de números pares, ímpares, positivos, negativos e zeros.
  - Busca de elementos por valor ou nome e identificação de índices.
  - Inversão de ordem e troca de posições em vetores.
  - Operações entre arrays (soma, comparação elemento a elemento).
  - Filtragem e manipulação de Strings.
  - Sistemas simples com menus de busca e controle de estoque.

- **Exercícios 31 a 50 (Matrizes / Arrays 2D):**
  - Criação, preenchimento e exibição formatada de matrizes.
  - Soma de todos os elementos, identificação de maior e menor valor.
  - Soma individual por linhas e por colunas.
  - Médias por linha (boletim escolar).
  - Identificação e soma dos elementos da diagonal principal e secundária.
  - Transposição de matrizes e multiplicação por escalar.
  - Troca de linhas e colunas.
  - Relatórios de vendas e controle de estoque por loja.

## 🚀 Como Executar

### Pré-requisitos
- **Java JDK** (versão 8 ou superior) instalado e configurado no sistema.

### Executando pelo Terminal

1. **Compilar todos os exercícios:**
   ```bash
   javac -d bin src/exercicios/arrays/*.java
   ```

2. **Executar um exercício específico:**
   Substitua o nome da classe pelo exercício desejado (por exemplo, `_1GuardandoNomes` ou `_38BoletimComNomes`):
   ```bash
   java -cp bin exercicios.arrays._1GuardandoNomes
   ```

### Executando pela IDE (IntelliJ IDEA / Eclipse / VS Code)
Basta abrir a pasta do projeto na sua IDE e executar o método `main` de qualquer um dos arquivos `.java` desejados.
