import java.util.Scanner;

public class AverageCalculator {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter the number of elements: ");
        int n = scanner.nextInt();
        int[] numbers = new int[n];
        int sum = 0;

        System.out.println("Enter the numbers:");
        for (int i = 0; i < n; i++) {
            numbers[i] = scanner.nextInt();
            sum += numbers[i];
        }

        double average = (double) sum / n;
        System.out.println("The average is: " + average);
    }
}



-----
import java.util.Scanner;

public class AverageCalculator {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter the number of elements: ");
        int n = scanner.nextInt();
        int[] numbers = new int[n];
        int sum = 0;

        System.out.println("Enter the numbers:");
        for (int i = 0; i < n; i++) {
            numbers[i] = scanner.nextInt();
            sum += numbers[i];
        }

        double average = (double) sum / n;
        System.out.println("The average is: " + average);
    }
}
--

<h1 align="center">
 <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=35&center=true&vCenter=true&width=500&height=70&duration=4000&lines=Hi+There!+👋;+I'm+MeoRslan!;" />
</h1>

<h3 align="center">on journey to improve the cyber skills 😈</h3>


<div align="center">
 
 🔭 I’m study now cyber security
 
 🌱 I’m currently learning CISSP

💬 Ask me about cyber security, design, programming, Licensing... or anything [here]

🫀{أفضل الصدقة أن يتعلم المسلم علما ثم يعلمه أخاه المسلم}🫀

⚡ Fun fact cyber security

 </div>
 
<div align="center"> 
  <a href="protonmail:rslandark@proton.me">
    <img src="https://img.shields.io/badge/Gmail-333333?style=for-the-badge&logo=gmail&logoColor=red" />
  </a>
  <a href="https://linkedin.com/in/meorslan" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank" />
  </a>
  <a href="https://meorslan.github.io" target="_blank">
     <img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=todoist&logoColor=white" target="_blank" /> <!-- sqlite, safari, google-chrome are other good icon options -->
  </a>
</div>


 
<h2 align="center">⚒️ Languages-Frameworks-Tools ⚒️</h2>

<div align="center">
    <img src="https://skillicons.dev/icons?i=react,bootstrap,mui,html,css,vscode,github,figma,tailwind,git,r" />
    <img src="https://skillicons.dev/icons?i=nodejs,python,nmap,typescript,express,firebase,linux,c,java,nextjs,mysql,kali" /><br>
</div>

https://share.note.sx/1vz4s727#h1MRVySfLPTJyYyEAylITo4c8nb+y3PwVVj6ZHMuaCE


[1.docx](https://github.com/user-attachments/files/17797230/1.docx)





Example: Program to Add Two Integers
class Main {

  public static void main(String[] args) {
    
    int first = 10;
    int second = 20;

    // add two numbers
    int sum = first + second;
    System.out.println(first + " + " + second + " = "  + sum);
  }
}

Example: Multiply Two Floating-Point Number

public class MultiplyTwoNumbers {

    public static void main(String[] args) {

        float first = 1.5f;
        float second = 2.0f;

        float product = first * second;

        System.out.println("The product is: " + product);
    }
}

Java Program to Compute Quotient and Remainder
public class QuotientRemainder {

  public static void main(String[] args) {

    int dividend = 25, divisor = 4;

    int quotient = dividend / divisor;
    int remainder = dividend % divisor;

    System.out.println("Quotient = " + quotient);
    System.out.println("Remainder = " + remainder);
  }
}

Java Program to Find the Largest Among Three Numbers
public class Largest {

    public static void main(String[] args) {

        double n1 = -4.5, n2 = 3.9, n3 = 2.5;

        if( n1 >= n2 && n1 >= n3)
            System.out.println(n1 + " is the largest number.");

        else if (n2 >= n1 && n2 >= n3)
            System.out.println(n2 + " is the largest number.");

        else
            System.out.println(n3 + " is the largest number.");
    }
}

Java Program to Find all Roots of a Quadratic Equation

public class Main {

  public static void main(String[] args) {

    // value a, b, and c
    double a = 2.3, b = 4, c = 5.6;
    double root1, root2;

    // calculate the discriminant (b2 - 4ac)
    double discriminant = b * b - 4 * a * c;

    // check if discriminant is greater than 0
    if (discriminant > 0) {

      // two real and distinct roots
      root1 = (-b + Math.sqrt(discriminant)) / (2 * a);
      root2 = (-b - Math.sqrt(discriminant)) / (2 * a);

      System.out.format("root1 = %.2f and root2 = %.2f", root1, root2);
    }

    // check if discriminant is equal to 0
    else if (discriminant == 0) {

      // two real and equal roots
      // discriminant is equal to 0
      // so -b + 0 == -b
      root1 = root2 = -b / (2 * a);
      System.out.format("root1 = root2 = %.2f;", root1);
    }

    // if discriminant is less than zero
    else {

      // roots are complex number and distinct
      double real = -b / (2 * a);
      double imaginary = Math.sqrt(-discriminant) / (2 * a);
      System.out.format("root1 = %.2f+%.2fi", real, imaginary);
      System.out.format("\nroot2 = %.2f-%.2fi", real, imaginary);
    }
  }
}

Java Program to Check Leap Year
public class Main {

  public static void main(String[] args) {

    // year to be checked
    int year = 1900;
    boolean leap = false;

    // if the year is divided by 4
    if (year % 4 == 0) {

      // if the year is century
      if (year % 100 == 0) {

        // if year is divided by 400
        // then it is a leap year
        if (year % 400 == 0)
          leap = true;
        else
          leap = false;
      }
      
      // if the year is not century
      else
        leap = true;
    }
    
    else
      leap = false;

    if (leap)
      System.out.println(year + " is a leap year.");
    else
      System.out.println(year + " is not a leap year.");
  }
}

Java Program to Check Whether a Number is Positive or Negative

public class PositiveNegative {

    public static void main(String[] args) {

        double number = 12.3;

        // true if number is less than 0
        if (number < 0.0)
            System.out.println(number + " is a negative number.");

        // true if number is greater than 0
        else if ( number > 0.0)
            System.out.println(number + " is a positive number.");

        // if both test expression is evaluated to false
        else
            System.out.println(number + " is 0.");
    }
}

Java Program to Check Whether a Character is Alphabet or Not

public class Alphabet {

    public static void main(String[] args) {

        char c = '*';

        if( (c >= 'a' && c <= 'z') || (c >= 'A' && c <= 'Z'))
            System.out.println(c + " is an alphabet.");
        else
            System.out.println(c + " is not an alphabet.");
    }
}

Java Program to Calculate the Sum of Natural Numbers

public class SumNatural {

    public static void main(String[] args) {

        int num = 100, sum = 0;

        for(int i = 1; i <= num; ++i)
        {
            // sum = sum + i;
            sum += i;
        }

        System.out.println("Sum = " + sum);
    }
}

Java Program to convert string variables to double
class Main {
  public static void main(String[] args) {

    // create string variables
    String str1 = "23";
    String str2 = "456.6";

    // convert string to double
    // using parseDouble()
    double num1 = Double.parseDouble(str1);
    double num2 = Double.parseDouble(str2);

    // print double values
    System.out.println(num1);    // 23.0
    System.out.println(num2);    // 456.6
  }
}

Java Program to convert double type variables to string

class Main {
  public static void main(String[] args) {

    // create double variable
    double num1 = 36.33;
    double num2 = 99.99;

    // convert double to string
    // using valueOf()
    String str1 = String.valueOf(num1);
    String str2 = String.valueOf(num2);

    // print string variables
    System.out.println(str1);    // 36.33
    System.out.println(str2);    // 99.99
  }
}




