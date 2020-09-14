<!-- URLs -->
[swift-imagem]: https://img.shields.io/badge/Swift-5.2-orange.svg?style=flat
[swift-url]: https://swift.org/
[xcode-imagem]: https://img.shields.io/badge/xcode-11.3-orange
[xcode-url]: https://developer.apple.com/xcode/

#  Digital House | iOS Swift | Exercícios | Venda Certa

Exercício da aula do dia 11/09/2020 (2020-09-11) referente a programação orientada a objetos com o pilar do encapsulamento.


[![Swift][swift-imagem]][swift-url]
[![Xcode][xcode-imagem]][xcode-url]

## Tópicos

- [Tópicos](#tópicos)
- [Requerimentos](#requerimentos)
  - [Swift](#swift)
  - [Xcode](#xcode)
  - [macOS](#macos)
- [Descrição](#descrição)

## Requerimentos

Para utilizar a aplicação é necessário atender os seguintes requisitos:

- Swift 5 ou superior
- Xcode 11.3 ou superior
- macOS 10.14 (Mojave) ou superior
- RAM 8GB ou superior
- HD 128GB ou superior

### Swift

Swift é uma linguagem de programação orientada a objetos, com tipagem forte e permite o desenvolvimento utilizado múltiplos paradigmas.
Mais informações podem ser obtidas clicando no seguinte link [Swift][swift-url].

### Xcode

É uma Ferramenta de Desenvolvimento Integrado ou IDE na sigla em inglês.
É a ferramenta sugerida pela Apple que é detentora da marca e da linguagem.

Mais informações, clique no link [Xcode][xcode-url].

### macOS

É o sistema operacional utilizado para o desenvolvimento de aplicativos mobile iOS.

É possível obter mais informações clicando no seguinte hyperlink [macOS](https://www.apple.com/br/macos/catalina/).

[Voltar ao menu](#tópicos)

## Descrição

O exercício possui a seguinte descrição:

<blockquote>
Temos uma loja de carros, o nome dela é Venda Certa. Essa loja tem um estoque de quantos carros tem no total na loja. No momento, eles tem 50 carros em estoque.
Para sair um carro do estoque, esse carro precisa ser vendido, não há outro modo de retirar produtos no estoque. Esse estoque também nunca pode ficar negativo.
A fábrica falou pra loja que se eles conseguirem vender pelo menos 5 carros de uma só vez, a fábrica vai dar 1 carro de bonificação pra loja. 
A fábrica também falou que, no momento que terminarem de vender todo estoque, a fábrica vai dar 2 carros de bonificação pra loja.
</blockquote>

<br>
Teste de mesa:
<br><br>

```
tem 50
se vende 1 fica com 49
tem 49
se vende 5 fica com 44
ganha 1 da fábrica
tem 45
vende 44 fica com 1
ganha 1 da fábrica
tem 2
vende 2 fica com 0
ganha 2 da fábrica
tem 2
```

[Voltar ao menu](#tópicos)