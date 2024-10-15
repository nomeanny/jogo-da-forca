# jogo-da-forca
Recursos utilizados no Jogo da Forca

## Aqui está uma lista dos recursos utilizados no Jogo da Forca:

## Variáveis:
palavra: armazena a palavra secreta digitada pelo usuário.
digitadas: armazena as letras já digitadas pelo usuário.
acertos: armazena as letras que estão na palavra secreta e foram adivinhadas pelo usuário.
erros: armazena o número de erros cometidos pelo usuário.
Estruturas de controle:
while True: cria um loop infinito que continua até que o usuário adivinhe a palavra secreta ou erre 6 vezes.
if e elif: utilizados para verificar se a letra digitada está na palavra secreta ou se o usuário já digitou essa letra antes.

## Funções:
input(): utilizada para obter a palavra secreta e as letras digitadas pelo usuário.
lower(): utilizada para converter a palavra secreta e as letras digitadas para minúsculas.
strip(): utilizada para remover espaços em branco da palavra secreta e das letras digitadas.

## Operadores:
==: utilizado para verificar se a letra digitada está na palavra secreta.
in: utilizado para verificar se a letra digitada está na lista de letras já digitadas.
+=: utilizado para adicionar letras à lista de letras já digitadas e à lista de letras adivinhadas.

## Desenho do enforcado:
Utiliza strings para criar o desenho do enforcado e atualiza-o à medida que o contador de erros aumenta.
