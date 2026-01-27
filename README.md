import java.util.Scanner;

public class App {
    public static void main(String[] args) throws Exception {
        Scanner ler = new Scanner(System.in);
        
//entrada e saida de dados 
        System.out.println("Vamos calcular! Digite os números  inteiros  que deseja: ");
        System.out.println("Qual o primeiro número? ");
        float num1 = ler.nextFloat();
        System.out.println("E qual é o proximo número? ");
        float num2 = ler.nextFloat();
        
//operações

float soma = num1 +num2;
float menos = num1 - num2;
float div = num1 / num2;
float vezes = num1 * num2;
float resto = num1 % num2;

 // resultados 
 
System.out.println("Primeiro vamos realizar a soma dos números, então: " +num1+" + "+num2+ " = "+soma);
System.out.println("Agora a subtração do números: " +num1+" - "+num2+ " = "+menos);
System.out.println("A divisão foi: " +num1+" / "+num2+ " = "+div);
System.out.println("Temos a multiplicação: " +num1+" X " +num2+ " = "+vezes);
System.out.println("E também  o resto da divisão: " +num1+" % "+num2+ " = "+resto);

ler.close();

System.out.println("Por hoje é só pessoal, até a próxima!");






    }
}
