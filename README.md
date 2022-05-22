# Modelos de Regressão para dados de concreto

Essa análise foi apresentada no seminário da disciplina **Modelos de Regressão**(EST5507) oferecida no âmbito do programa [PIPGEs](https://www.pipges.ufscar.br/). Os dados analisados são dados de um experimento com concreto. Eles se encontram disponíveis no repositório do UCI neste [link](https://archive.ics.uci.edu/ml/datasets/Concrete+Compressive+Strength).

No artigo original, 

[I-Cheng Yeh, "Modeling of strength of high performance concrete using artificial neural networks," Cement and Concrete Research, Vol. 28, No. 12, pp. 1797-1808 (1998)](https://www.sciencedirect.com/science/article/abs/pii/S0008884698001653) 

foi proposto um modelo de redes neurais devido a não linearidade na relação entre as variáveis preditoras e a resistência do concreto. **Entretanto**, neste trabalho, criamos um modelo de **regressão linear gaussiano** onde a linearidade foi relaxada por meio de splines cúbicos restritos. O modelo apresentado neste relatório satisfez todas hipóteses do modelo linear gaussiano e ainda trouxe a vantagem da interpretabilidade.

