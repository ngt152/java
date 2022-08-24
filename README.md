import java.util.Scanner;

public class JavaApplication1 {

 
    public static void main(String[] args) {
        Scanner entrada = new Scanner(System.in);
       
        int a = 0;
        double sal = 0;
       
        System.out.println("Qual a quantidade de carros vendidos pelo funcionario: ");
        a = entrada.nextInt();
       
        if(a>5){
            sal = a*1000;
        }
        else{
            sal = a*500;
        }
       
        sal = sal + 1000;
       
        System.out.println("O salario total do funcionario é: "+ sal);
               
   
        }
       
}
