# Projeto-mobile01

Histórias de Usuário
História 1: Autenticação (Login)

Como morador
Quero entrar no sistema utilizando meu e-mail e senha
Para poder administrar minhas reservas.

Cenário 1: Login realizado com sucesso

Dado que estou na tela de login
E informo um e-mail válido
E digito a senha correta
Quando pressiono o botão “Acessar”
Então devo ser direcionado para a tela de reservas.

Cenário 2: Falha no login

Dado que estou na tela de login
E preencho informações inválidas
Quando clico em “Acessar”
Então o sistema deve exibir uma mensagem de erro.

História 2: Cadastro de Usuário

Como um novo morador
Quero criar uma conta no sistema
Para conseguir realizar reservas.

Cenário 1: Cadastro efetuado com sucesso

Dado que estou na tela de cadastro
E preencho corretamente o e-mail, senha e confirmação de senha
Quando clico em “Cadastrar”
Então minha conta deve ser criada no sistema.

Cenário 2: Senhas não correspondem

Dado que estou na tela de cadastro
E informo senhas diferentes
Quando tento concluir o cadastro
Então o sistema deve mostrar uma mensagem de erro.

História 3: Visualizar Áreas Disponíveis

Como morador
Quero visualizar as áreas disponíveis (quadras ou campo)
Para escolher onde realizar minha reserva.

Cenário 1: Exibição das áreas

Dado que estou na tela de reservas
Quando acesso a listagem de áreas
Então devo visualizar opções como:

Quadra de Tênis

Quadra Poliesportiva

Campo de Futebol

História 4: Escolher Data da Reserva

Como morador
Quero selecionar uma data no calendário
Para agendar minha reserva.

Cenário 1: Seleção da data

Dado que estou na tela de agendamento
Quando escolho uma data disponível
Então a data selecionada deve ficar destacada.

História 5: Escolher Horário

Como morador
Quero selecionar um horário disponível
Para definir quando utilizarei a área reservada.

Cenário 1: Horário disponível

Dado que já selecionei uma data
Quando escolho um horário livre
Então esse horário deve ser destacado.

Cenário 2: Horário indisponível

Dado que já selecionei uma data
E existem horários já ocupados
Quando visualizo a lista de horários
Então os horários indisponíveis devem aparecer desativados.

História 6: Confirmar Reserva

Como morador
Quero confirmar minha reserva
Para garantir o uso da área selecionada.

Cenário 1: Confirmação da reserva

Dado que escolhi a área, a data e o horário
Quando clico no botão “Confirmar”
Então a reserva deve ser registrada
E exibida na tela de confirmação.

História 7: Visualizar Reserva Confirmada

Como morador
Quero visualizar os detalhes da minha reserva
Para acompanhar meus agendamentos.

Cenário 1: Exibição da reserva

Dado que já tenho uma reserva realizada
Quando acesso a tela de confirmação
Então devo visualizar as seguintes informações:

Área reservada

Data

Horário

Nome do morador

História 8: Criar Nova Reserva

Como morador
Quero iniciar uma nova reserva
Para agendar outro horário.

Cenário 1: Iniciar nova reserva

Dado que estou na tela de confirmação da reserva
Quando clico no botão “Nova Reserva”
Então devo retornar ao fluxo de agendamento.
