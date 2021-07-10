# geolocation_optimization_ACO

Time-Dependent Vehicule Routing Problem (TDVRP) -- Ant Colony Optimization (ACO) + Geolocation 

O problema de roteamento de veículos (VRP) é um problema na área da otimização combinatória. 
Consiste no atendimento de um conjunto de consumidores por intermédio de uma frota de veículos, que partem de um ou mais pontos denominados depósitos.
Além disso, possui a restrição de capacidade do veículo.

Nesse caso, o problema consiste no time-dependent VRP, ou seja, o tempo da rota deve ser minimizado.

Portanto, o problema consiste em encontrar as rotas ótimas, ou seja, a sequência ótima dos pontos de geolocalização (latitude e longitude) minimizando oo tempo da rota. Estes dados podem ser, por exemplo, pontos de parada de ônibus.

A rota inicia em um ponto definido e chega em outro ponto definido. 

É necessário respeitar as restrições de tempo e capacidade de pessoas por ônibus.

Restrições:

1) Tempo total da rota: 120 min

2) Tempo de espera em cada parada: 1 min

3) Capacidade máxima de pessoas por ônibus: 60 pessoas

Resultado:


![image](https://user-images.githubusercontent.com/18504119/125176485-1c466f00-e1aa-11eb-970d-29dca8c673b4.png)


Instalação dos pacotes:
- OpenStreetMap: pip install osmnx
- Folium: pip install folium
