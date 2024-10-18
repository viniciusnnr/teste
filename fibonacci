#include <stdio.h>

int main() {
  int NumeroInformado;
  int soma;
  int FibonacciPrimeiro = 0;
  int FibonacciSegundo = 1;
  
  printf("digite o número que deseja verificar se está presente na sequência de Fibonacci \n");
  scanf("%d", &NumeroInformado);
  
  if( NumeroInformado == FibonacciPrimeiro || NumeroInformado == FibonacciSegundo){
        	printf("o valor está na sequência de fibo");
  };
 
   for (int i = 1; NumeroInformado > FibonacciSegundo; i++) {
        soma = FibonacciPrimeiro + FibonacciSegundo;  
		FibonacciPrimeiro = FibonacciSegundo;
        FibonacciSegundo = soma;
    
        if (NumeroInformado == FibonacciSegundo){
        	printf("o valor está na sequência de fibo");
        }else if (NumeroInformado < FibonacciSegundo){
        	printf("o valor não está");
        };
    }
  return 0;
}
