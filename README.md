# Recrutamento iOS

## Sobre o exercício
- Um app para conversão de moedas.
- O app deve conter 2 telas
    - A primeira, o usuário deve selecionar a moeda inicial (ex: Real) e o valor (ex: R$ 12,00);
    - Na segunda, o usuário entrará com os valores de "taxa de conversão"(ex: R$ 5,00) e sua moeda e selecionar a "moeda destino" (ex: Dólar) que deseja converter o valor do balance. 
    - A taxa pode ser cobrada no valor de outra moeda - ex: 5 euros
    - Ao calcular, o valor final deve ser o valor inicial convertido para o valor destino, subtraindo o valor de taxa na moeda selecionada também.

## Exemplo
```
- valor inicial = 10
- moeda inicial = dólar

- taxa de conversão = 2
- moeda da taxa = euro
- moeda destino = real
- considerando o dólar 5x o valor do real, e o euro 6x o valor do real, temos:
    - valor final = (10 * 5) - (2 * 6) => 38 reais
```

## Requisitos
- Criar um módulo de conversão de moedas separado do módulo principal da aplicação; Pode ser feita como framework ou pod ou swift package, por exemplos.
- Criar cobertura de testes unitários, para o módulo de conversão;
- Camada de rede, você pode utilizar lib, mas o parse deve ser feito sem o uso da mesma.

## Dicas
- Explore ao máximo os requisitos obrigatórios
- Como sugestão, a API https://exchangeratesapi.io/ é totalmente grátis e versátil

---

[Merci @ 2021](https://merci.com.br)
