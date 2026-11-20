## Marketplace Profit Calculator

Aplicativo desktop em Java/Swing que compara o lucro estimado de uma venda em Shopee, TikTok Shop, Mercado Livre e Amazon.

O programa recebe o preco de venda, o custo do produto e a comissao de afiliado do TikTok. Ele tambem permite marcar a opcao `CPF (+R$ 3,00)`, usada nos calculos da Shopee e do Mercado Livre. A interface exibe taxas, repasse liquido, lucro bruto e margem bruta para cada plataforma, além de indicar a melhor opcao.

## Requisitos

- JDK com os comandos `javac` e `java`
- Ambiente desktop com suporte a uma interface grafica Java (Swing)

Nao ha dependencias externas ou sistema de build configurado neste repositorio.

## Executar

Na raiz do repositorio, compile e execute:

```bash
javac -d bin src/Calculadora.java
java -cp bin Calculadora
```

No VS Code, tambem e possivel abrir `src/Calculadora.java` e executar o metodo `main` com uma extensao Java instalada.

## Uso

Preencha `Preco de venda (R$)`, `Seu custo do produto (R$)` e `Comissao afiliado TikTok (%)`. Use ponto ou virgula como separador decimal. Clique em `CALCULAR` para atualizar os quatro cards.

Campos vazios ou valores invalidos exibem uma mensagem de erro.

## Estrutura do projeto

- `src/Calculadora.java`: codigo-fonte da interface e dos calculos
- `bin/` e `out/`: diretorios que podem conter os arquivos `.class` gerados localmente
