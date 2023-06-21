# problem3.java
java
import java.util.Scanner;

public class Series1 {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Enter a number: ");
        int a = scanner.nextInt();

        System.out.print(1 + " ");

        for (int i = 2; i <= a; i++) {
            int nextTerm = 2 * i - 1;
            System.out.print(nextTerm + " ");
        }
    }
}
