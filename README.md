# L..L-PROJECT
#CÓDIGO #L_L SOLUÇÕES
package scaner;

import java.util.Scanner;

public class Imc01cc{

    public static void main(String args[]) {
      

        float peso , altura , calc ;

        Scanner result = new Scanner(System.in);
        System.out.println("digite seu peso: ");
        peso = result.nextFloat();
        System.out.println("digite sua altura: ");
        altura = result.nextFloat();
        calc = (peso) / (altura * altura);
        System.out.printf("seu ImC é: %f",calc);

        if (calc < 20) {
            System.out.println("magro");
        }
            else if( calc<=24 &&  calc>=20){
   System.out. println("normal");
        }
            else if ( calc>=25 && 29>calc) {
            System.out.println("acima do peso");
        }
        if (calc >= 30 &&  calc<= 34) {
           System.out.println("obeso");
        }
        if (calc > 34) {
           System.out. println("muito obeso");
        }
    }
}

   
