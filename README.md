Sistema de Gerenciamento de Veículos

Bem-vindo a uns de meus projetos feito em .net C# - um sistema de gerenciamento de veículos para estacionamento. Esta aplicação permite o gerenciamento eficiente de veículos estacionados, incluindo funções para adicionar veículos, calcular valores de estacionamento e listar os veículos presentes.

## Funcionalidades

O **Estacionamento** oferece as seguintes funcionalidades:

### Adicionar Veículo

O método `AdicionarVeiculo(placa: string)` permite adicionar um novo veículo à lista de veículos estacionados.

### Remover Veículo

O método `RemoverVeiculo(placa: string, horasEstacionado: int)` verifica se um veículo está estacionado, calcula o valor a ser pago com base no tempo de estacionamento e exibe o valor para o usuário.

### Listar Veículos

O método `ListarVeiculos()` exibe a lista de veículos estacionados no momento. Caso não haja veículos estacionados, exibirá a mensagem "Não há veículos estacionados".

### Menu Interativo

A aplicação possui um menu interativo com as seguintes opções:

1. Cadastrar veículo
2. Remover veículo
3. Listar veículos
4. Encerrar

## Diagrama de Classe

A estrutura do programa é baseada no seguinte diagrama de classe:

![Diagrama de Classe Estacionamento](diagrama_classe_estacionamento.png)

## Uso

1. Clone ou faça o download do repositório.
2. Abra o projeto em um ambiente de desenvolvimento .NET compatível.
3. Execute o programa acessando a pasta com o arquivo .csproj e em seguida digitando no console o comando `dotnet run`.
4. Utilize o menu interativo para gerenciar os veículos no estacionamento.

## Exemplo de Uso

Bem-vindo ao Estacionamento!

Escolha uma opção:
1. Cadastrar veículo
2. Remover veículo
3. Listar veículos
4. Encerrar

Opção: 1

Digite a placa do veículo: ABC123

Veículo cadastrado com sucesso!

Escolha uma opção:
1. Cadastrar veículo
2. Remover veículo
3. Listar veículos
4. Encerrar

Opção: 3

Veículos estacionados:
1. ABC123

Escolha uma opção:
1. Cadastrar veículo
2. Remover veículo
3. Listar veículos
4. Encerrar

Opção: 2

Digite a placa do veículo a ser removido: XYZ987
Digite o número de horas que o veículo permaneceu estacionado: 3

Valor a ser pago: R$ 15.00

Escolha uma opção:
1. Cadastrar veículo
2. Remover veículo
3. Listar veículos
4. Encerrar

Opção: 4

Obrigado por usar o Estacionamento!


## Conclusão

O **Estacionamento** é uma aplicação completa do tipo Console para gerenciamento de veículos estacionados, oferecendo funcionalidades para adicionar, remover e listar veículos, bem como um menu interativo para fácil navegação. Este projeto demonstra a aplicação de conceitos fundamentais da trilha .NET da DIO.

Projeto desenvolvido como parte da Trilha .NET da Digital Innovation One (DIO). Para mais informações, visite [www.dio.me](www.dio.me).

