# SIRmodel
Per compilare il progetto abbiamo due possibili strade:

> ## ATTRAVERSO CMAKE (ninja file)

Come scaricare ninja(Ubuntu):
```
sudo apt-get install ninja
```
Passiamo alla compilazione:
```
cd SIRmodel
cd option1 (cd option2)
cd build
cmake -G Ninja ..
ninja 
./sir-sfml
```
> ## DA TERMINALE:
```
g++ -c main.cpp
g++ main.o -o sfml-app -lsfml-graphics -lsfml-window -lsfml-system
./sfml-app
```
