# Vehicle-Classification-CNN

# Informações Gerais
Este projeto foi minha submissão ao Desafio Final do curso de extensão "Introdução a Machine Learning e Deep Learning com Python e PyTorch", oferecido pela Brasil+IA. 

O desafio consistiu na criação de um modelo classificador de imagens de veículos pré-definidos no enunciado do exercício. O dataset podia conter imagens dos veículos Farrari Enzo, Fiat Uno Way, Hummer H1, Kawasaki Ninja, Volkswagen Worker ou imagens de estradas vazias. 

Para a realização desse desafio, precisei realizar as seguintes tarefas:
* Montar o dataset de imagens dos veículos para treinar e validar o modelo, utilizando a biblioteca Fast.ai. 
* Implementar uma rede neural convolucional, podendo utilizar transfer learning.
* Escolher os parâmetros e calibrar os hiperparâmetros para obter a melhor acurácia possível.
* Salvar o modelo treinado para que ele fosse testado pela equipe pedagógica do curso.
* Implementar uma função que recebesse uma imagem de qualquer um dos veículos listados no enunciado do exercício e retornasse o número da categoria daquele veículo.

# Resultados
* O dataset montado consiste de 4435 imagens de todas as categorias.
* A acurácia obtida pelo modelo foi de **98.87%.**
* A acurácia obtida pela equipe pedagógica do curso ao realizar um teste com um dataset inédito ao modelo foi de **97.77%**, sendo este o terceiro melhor resultado obtido entre os 22 alunos.
