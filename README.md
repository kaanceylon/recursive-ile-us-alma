# recursive-ile-us-alma
import java.awt.*;
import java.sql.PreparedStatement;
import java.util.Scanner;

public class Main {

    static int power(int a, int b){
        int total =1;
        for (int i=1; i<=b; i++){
            total*=a;
        }
       return total;
    }

    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        int a, b;
        System.out.print("Tabandaki sayiyi giriniz: ");
        a = input.nextInt();
        System.out.print("üsteki sayiyi giriniz: ");
        b = input.nextInt();

        System.out.println(power(a,b));

    }
}
































