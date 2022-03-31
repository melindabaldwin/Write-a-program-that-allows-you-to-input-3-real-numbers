# Write-a-program-that-allows-you-to-input-3-real-numbers
This program will check these 3 numbers are 3 sides of a triangle or not.
import java.util.Scanner;

public class BaiTapJavaCoBan3 {
    public static void main(String[] args)
    {
       float a, b, c;
       System.out.println("Enter 3 numbers:");
       Scanner sc = new Scanner(System.in);

       a = sc.nextFloat();
       b = sc.nextFloat();
       c = sc.nextFloat();

       if(a+b>c && b+c>a && c+a>b)
          System.out.println("Three correct numbers are 3 sides of a triangle");
       else
          System.out.println("Three numbers are not the 3 sides of a triangle");
    }
}
