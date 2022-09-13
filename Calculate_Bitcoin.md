import java.util.Scanner;

public class Calculate_Bitcoin {
    public static void main(String[] args){
        Scanner num = new Scanner(System.in);
        float courseBitcoin, dollar, result;

        System.out.print("What is Bitcoin price today?: ");
        courseBitcoin = num.nextFloat();

        System.out.print("How much $ do You have?: ");
        dollar = num.nextFloat();

        result = dollar / courseBitcoin;
        System.out.println("Result = " + result);
    }
}
