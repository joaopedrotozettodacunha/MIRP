#[English version below]

# Maritime Inventory Routing Problem (MIRP)

Este repositório reúne a implementação e a avaliação de desempenho de versões sequencial e paralela de uma heurística baseada em Otimização por Colônia de Formigas (ACO), aplicada ao Problema de Roteamento Marítimo com Gestão de Estoques (Maritime Inventory Routing Problem – MIRP).

O estudo foi conduzido utilizando instâncias de benchmark do **Grupo 2 da biblioteca [MIRPLib](https://mirplib.scl.gatech.edu/instances)**, contendo 72 instâncias com diferentes configurações e horizontes de planejamento.

## Objetivo

O principal objetivo é comparar as versões sequencial e paralela do ACO aplicadas ao MIRP, considerando métricas como valor da função objetivo, tempo de execução, speedup e eficiência paralela.

## Estrutura do repositório

```text
MIRP/
├── instances/
│   └── group2/
├── src/
│   ├── sequential/
│   └── parallel/
├── results/
├── README.md
└── requirements.txt
```

# Maritime Inventory Routing Problem (MIRP)

This repository contains the implementation and performance evaluation of sequential and parallel versions of an Ant Colony Optimization (ACO)-based heuristic applied to the Maritime Inventory Routing Problem (MIRP).

The study uses benchmark instances from **Group 2 of the [MIRPLib](https://mirplib.scl.gatech.edu/instances) library**, comprising 72 instances with different configurations and planning horizons.

## Objective

The main objective is to compare the sequential and parallel versions of ACO applied to the MIRP, considering metrics such as objective function value, execution time, speedup, and parallel efficiency.

## Repository Structure

```text
MIRP/
├── instances/
│   └── group2/
├── src/
│   ├── sequential/
│   └── parallel/
├── results/
├── README.md
└── requirements.txt
```





