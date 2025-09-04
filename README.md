# Jogo-de-Pedra-Papel-Tesoura
This is a small first project i made in python language.

import random

opções = ['pedra', 'papel', 'tesoura']
computador = random.choice(opções)
jogador = str(input('Escolha pedra, papel ou tesoura: '))

if jogador == computador:
    print('Empate!')
elif jogador == 'pedra' and computador == 'tesoura':
    print('Você ganhou! Computador escolheu tesoura.')
elif jogador == 'papel' and computador == 'pedra':
    print('Você ganhou! Computador escolheu pedra.')
elif jogador == 'tesoura' and computador == 'papel':
    print('Você ganhou! Computador escolheu papel.')
else:
    print('Você perdeu! Computador escolheu:', computador)
