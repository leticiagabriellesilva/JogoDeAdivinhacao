import java.util.Scanner;
import java.util.Random;

public class ExercicioLoop {
    public static void main(String[] args) {
        // Objetivo: jogo de adivinhação com Java, utilizando o laço while e new Random.
        Scanner leitura = new Scanner(System.in);
        int aleatorio = new Random().nextInt(100);
        int tentativas = 0;

        while (tentativas < 5){
            System.out.println("Digite um número: ");
            int numero = leitura.nextInt();
            tentativas++;
            if (numero == aleatorio) {
                System.out.println("Parabéns, você acertou com " + tentativas + " tentativas!");
                break; 
            } else if (numero > aleatorio) { // quando é numero < aleatorio não funciona da forma correta
                System.out.println("Errou, dica: o número é menor");
            } else {
                System.out.println("Errou, dica: o número é maior");
            }
        }
        if (tentativas == 5) {
            System.out.println("Acabou as tentativas, o número era " + aleatorio);
        }
}
}
