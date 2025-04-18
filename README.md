# Backend - Algoritmos de Busca para Peças Automotivas

Este projeto foi desenvolvido como parte de uma atividade acadêmica para aplicar três algoritmos fundamentais em ciência da computação diretamente no backend de um sistema de gerenciamento de peças automotivas.

## 🔧 Funcionalidades Implementadas

### 1. Quick Sort (Ordenação Total)
Permite ordenar os dados com base em qualquer coluna numérica (ex: compras mensais), em ordem crescente ou decrescente, diretamente via algoritmo Quick Sort implementado manualmente em Python.

### 2. Heap (Ordenação Parcial)
Retorna os **K maiores** ou **K menores** valores de uma determinada coluna utilizando `heapq`, através das funções `nlargest` e `nsmallest` do Pandas.

### 3. Autocomplete com Árvore Binária de Busca (BST)
Utiliza uma BST para permitir sugestões de produtos com base em prefixos digitados. Ao buscar, o sistema retorna até 5 sugestões que começam com o texto informado.

---

## 📁 Estrutura do Arquivo

- `backend_algoritmos_busca.py` - Script principal com as funções e exemplos de uso.
- Requer o arquivo CSV com o nome `Peças Automotivas.csv` no mesmo diretório.

---

## ▶️ Como Executar

1. Coloque seu arquivo `Peças Automotivas.csv` no mesmo diretório.
2. Execute o script com Python:
```bash
python backend_algoritmos_busca.py
```

---

## 🧠 Tecnologias e Conceitos Utilizados

- Python 3
- Pandas
- Estrutura de Dados: Lista, Heap, Árvore Binária
- Algoritmos: Quick Sort, Heap, Autocomplete com BST

---

## 💡 Exemplos no Código

- Ordenar por “Compras mensais” em ordem decrescente
- Obter os 5 maiores compradores
- Autocompletar peças com prefixo “fi” (ex: “Filtro de Óleo”)

---

## 📚 Autor
Desenvolvido por um estudante de Engenharia de Software – 4º semestre, como parte da disciplina *Estrutura de Dados com Aplicações Reais*.
