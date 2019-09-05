# Desafio BackEnd Sênior

----
Uma corrida de Fórmula 1 aconteceu e precisamos de algumas informações à partir de alguns dados fornecidos. 
Foi disponibilizado três arquivos com informações desta corrida em específico, que são as seguintes:

**Arquivo "largada.txt"** = Posição em que cada piloto largou na corrida.

```
Largada    Codigo   Piloto                 Equipe
1	       33	    Max Verstappen	       Red Bull
2	       77	    Valtteri Bottas	       Mercedes
3	       44	    Lewis Hamilton	       Mercedes
4	       16	    Charles Leclerc	       Ferrari
5	       5	    Sebastian Vettel       Ferrari
...
```

**Arquivo "log-da-corrida.txt"** = Telemetria de cada piloto na corrida.

```
Codigo 33
Volta 1
Tempo 1:02.274
Codigo 33
Volta 2
Tempo 1:02.950
Codigo 33
Volta 3
Tempo 1:01.217
Codigo 33
...
```

**Arquivo "pitstop.txt"** = Paradas de pitstop de cada piloto na corrida.

```
Codigo 18
Volta 7
Tempo 0:04.032
Codigo 88
Volta 7
Tempo 0:04.400
Codigo 3
Volta 8
Tempo 0:04.398
...
```

----
## Observação
Os arquivos à serem utilizados estão na raiz deste repositório.

----
## Precisamos das seguintes informações:

* **Resultado final da corrida**
	* Posição de chegada
	* Quantidade de posições que ganhou ou perdeu comparado à largada (positivo ou negativo)
	* Código do piloto
	* Nome do piloto
	* Nome da equipe
	* Tempo da melhor volta
	* Tempo da pior volta
	* Diferença de tempo entre o piloto e o primeiro lugar
	* Tempo total da prova

----
* **O melhor piloto de cada equipe**
	* Nome da equipe
	* Piloto
	* Diferença de tempo total entre o piloto e seu parceiro de equipe

----
* **O melhor e pior piloto por volta**
	* Número da volta
	* Nome do melhor piloto
	* Tempo do melhor piloto
	* Nome do pior piloto
	* Tempo do pior piloto
	* Diferença de tempo entre os dois

----
# Requisitos
Faça a leitura dos arquivos citados, e exiba os  resultados da maneira que preferir (ex. site html, wpf, webforms, mobile, etc): 

----
# Tecnologias que você pode utilizar
A solução poderá ser desenvolvida em qualquer linguagem da sua escolha com quaisquer frameworks/plugins/pacotes. 

----
# Bônus

* Criar uma aplicação de ponta-a-ponta (Frontend + Backend)
* Utilizar API's
* Ser criativo

----
# O que será avaliado e também gostaríamos de ver

* Clean code
* Código bem estruturado
* Qualidade do código
* Tratamento de erros
* Separação de responsabilidades
* Evitar comentários

----
# Observações

* Não faça um fork desse projeto. Crie um repositório no seu perfil do GitHub/BitBucket e nos envie a url;
* Criar uma documentação em markdown (ReadMe) explicando como as aplicações devem ser executadas, quais os pre-requisitos para as mesmas, e passo a passo de scripts caso houver (banco de dados, etc);
* No final do Readme criar uma sessão chamada **Resultado** e descrever todos os príncipais desafios e linhas de raciocínio (Sim, presamos por uma explicação clara e objetiva).



