# java_session1_assignment1
java_session1_assignment1

// 1.Program to print the output of the a and b

public class calculation {
	public static void main(String[] args) 
	{
		int a=20,b=10;
		int check=a--;
		int check1=--a;
		System.out.println("value of a--:" +check);
		System.out.println("value of --a:" +check1);
		
		b=(a--) - (--a);
		
		System.out.println("value of b is:" +b);
		int c=a--;
		System.out.println("value of c is:" +c);
		
		int d=a>>2;
		System.out.println("value of d is:" +d);
		
		int e=a&b;
		System.out.println("value of e is:" +e);
	}

}


//2.Program to print the aplhabets corresponding to Ascii values

public class Ascii {
	public static void main(String[] args)
	{
		char alpha;
		System.out.println("Ascii values are:");
		for(int i=65;i<=90;i++)
		{
			
		System.out.println(+i+" -"+(char)i);
	}
		}

}

//3.Reversing the values of two numbers
 
package assignment1;
import java.io.*;
import java.util.*;

public class reversenum {
public static void main(String[] args)
{
	int sum;
	System.out.println("Enter the 1st number:");
	Scanner s=new Scanner(System.in);
	int a=s.nextInt();
	System.out.println("Enter the second number:");
	int b=s.nextInt();
	a=a+b;
	b=a-b;
	a=a-b;
	System.out.println("Now the 1st number is:" +a);
	System.out.println("Now the second number is:" +b);
	
}
}

