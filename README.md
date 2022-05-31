# tp2_td2
Trabajo Practico 2 - TDII


- Ejecucion de Prueba: 

  > Compilacion :
                gcc preba.c main.c -o prueba
               
  > Ejecucion:
                ./prueba
                
  > Memory check:
                 valgrind --leak-check=full --show-leak-kinds=all -v ./prueba
                 
             
- Ejecucion Final: 

  > Compilacion :
                gcc trencito.c main.c -o tren
               
  > Ejecucion:
                ./tren
                
  > Memory check:
                 valgrind --leak-check=full --show-leak-kinds=all -v ./tren
