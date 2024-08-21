# Assignment-2
import java.util.Scanner;
public class Calculator {
    public static void main(String[] args) {
     
        Scanner number = new Scanner(System.in);
        System.out.print("nhap so thu nhat: ");
        int num1 = number.nextInt();

        System.out.print("nhap so thu hai: ");
        int num2 = number.nextInt();
        System.out.println(num1 + " + " + num2 + " = " + (num1 + num2));
        System.out.println(num1 + " - " + num2 + " = " + (num1 - num2));
        System.out.println(num1 + " * " + num2 + " = " + (num1 * num2));
        
        if (num2 != 0) {
            System.out.println(num1 + " / " + num2 + " = " + ((double) num1 / num2));
            System.out.println(num1 + " % " + num2 + " = " + (num1 % num2));
        } else {
            System.out.println("khong the chia cho 0.");
        }
    }
}
