# NumberGame
package com.springcore.Dsa;
import java.util.Scanner;
import java.util.Random;


public class Numberguess {
	public static void main(String[] args) {
		Scanner scn = new Scanner(System.in);
		Random rand = new Random();
		int numberoftries = 0;
		int randnumber = rand.nextInt(100)+1;
		
				
		System.out.println("enter your guess(1-100)");
		int playerguess=s1.nextInt();
		numberoftries++;
		
		if(playerguess==randnumber) {
			System.out.println("correct option choose");
			
		}
		else if(randnumber>playerguess) {
			System.out.println("nope the number is higher");
			
		}
		else {
			System.out.println("nope the numer is lower");
			
		}
	}
}
