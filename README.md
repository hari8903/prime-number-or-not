package org.conditional;
import java.util.Scanner;
public class number {
	static Scanner s=new Scanner(System.in);
	public static void main(String[] args) {
		System.out.println("enter the number");
		int p=s.nextInt();
		int count=0;
		if(p==0||p==1) 
		{
			System.out.println("this is not allow the prime number");	
		}
		else
		{
		for(int i=1; i<=p; i++) 
		{
		      if(p%i==0) 
		      {
		    	  count++;
		      }
		}
		}
		if(count==2) {
		System.out.println("this is prime number");
		}
		else
		{
			System.out.println("this is not prime number");
		}	
	}
}
