_(English version below)_

# Metaheurystyki

## Problem kliki

_(Projekt zrealizowany w 2023 r. w trakcie kursu z zakresu metaheurystyk, w ramach studiów inżynierskich na kierunku
informatyka na Polsko-Japońskiej Akademii Technik Komputerowych w Gdańsku)._

**Klika** w grafie nieskierowanym _G_ o wierzchołkach _V_ i krawędziach _E_ ( _G = (V, E)_ ) jest podzbiorem
wierzchołków _V'_ należacych do V ( _V' ⊆ V_ ), w którym każda para wierzchołków jest połączona krawędzią należącą do
E – klika jest pełnym podgrafem grafu G. Rozmiarem kliki jest liczba wierzchołków, które klika zawiera.

Mianem **problemu kliki** określa się optymalizacyjny problem znalezienia w danym grafie kliki o maksymalnym rozmiarze.
W wersji decyzyjnej problem ten sprowadza się do odpowiedzi na pytanie, czy w grafie _G_ istnieje klika o rozmiarze _k_.

Algorytm „naiwny“ dla problemu kliki w wersji decyzyjnej – dla odpowiedzi na pytanie, czy graf _G = (V, E)_ (o liczności
zbioru wierzchołków _|V|_ ) zawiera klikę rozmiaru _k_ – sprowadza się do przejrzenia wszystkich _k_-podzbiorów zbioru
_V_ i sprawdzenia każdego z nich, czy nie tworzy on kliki.

Czas działania powyższego algorytmu wynosi Ω ( C ( _|V|_ , _k_ ) k^2 ) i jest to czas wielomianowy, o ile _k_ jest
wartością stałą. Jeśli natomiast _k_ nie ma stałej wartości – może się zmieniać – czas działania algorytmu będzie czasem
wykładniczym. Efektywny algorytm dla rozwiązania problemu kliki najprawodpodobniej nie istnieje.

Przygotowano w oparciu o: T. H. Carmen, C. E. Leiserson, R. L. Rivest, C. Stein, _Wprowadzenie do algorytmów_, tłum. K,
Diks, A. Malinowski, D. Roszkowska i W. Rytter, wyd. VII, Warszawa 2021.

# Metaheuristics

## The clique problem

_(This project undertaken in 2023 during the metaheuristics course, as a part of the bachelor's degree programme in
computer science at Polsko-Japońska Akademia Technik Komputerowych, Gdańsk)._

A **clique** in an undirected graph _G_ with vertices _V_ and edges _E_ ( _G = (V, E)_ ) is a subset of vertices _V'_
belonging to V ( _V' ⊆ V_ ), in which every pair of vertices is connected by an edge belonging to
E; the clique is a complete subgraph of the graph G. The size of a clique is the number of vertices that the clique
contains.

The **clique problem** is referred to as the optimization problem of identifying the clique of maximum size in a given
graph. In its decision variant, this problem comes down to answering the question, whether a clique of size _k_ exists
in the graph _G_.

The 'naive' algorithm for the clique problem in its decision variant - for answering the question, whether the graph
_G = (V, E)_ (of set of vertices size _|V|_ ) contains a clique of size _k_ - amounts to looking through all _k_-subsets
of the set of _V_ and checking each of them to see if it forms a clique.

The running time of the above algorithm is Ω ( C ( _|V|_ , _k_ ) k^2 ) and it is polynomial time as long as _k_ is a
constant. If, on the other hand, _k_ is not a constant value - it may vary - the running time of the algorithm will be
an exponential. Most likely, the efficient algorithm for solving the clique problem does not exist.

Prepared based on: T. H. Carmen, C. E. Leiserson, R. L. Rivest, C. Stein, _Introduction to Algorithms_, transl. K,
Diks, A. Malinowski, D. Roszkowska and W. Rytter, 7th ed., Warsaw 2021.