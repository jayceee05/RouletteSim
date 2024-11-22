# RouletteSim
Java program that simulates a roulette and gives prizes at random

Creates and array with 10 different prizes and chooses 30 random numbers between 1 and 50 and adds them to a priority queue. The 10 first choosen numbers are put in a HashTable and are assigned a prize. Following the priority queue, the winning numbers are printed. If the number is found in the hashTable the prize is printed with it, otherwise a small cash prize is given.
