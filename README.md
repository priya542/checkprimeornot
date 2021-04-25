# checkprimeornot
to check whether a number is prime number or not

import java.util.Scanner;

public class Primeornot {

	public static void main(String[] args) {
	 @SuppressWarnings("resource")
	Scanner sc = new Scanner(System.in);
			System.out.println("Enter a value");
			int num = sc.nextInt();
			boolean isPrime = true;
			int i;
			for(i=2;i<num;i++){
				
				if(num%i==0) {
					isPrime = false;
					break;
				}
				
			}
					
					
				if(isPrime) {
					System.out.println( num + "is prime num");
				}else {
					System.out.println(num + "is not a prime num");
				}
			
		
		}
				
	}

		
				

	

