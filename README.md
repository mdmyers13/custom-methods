# custom-methods
My first lab using custom methods

//Author:  MDM
//Source File:  Methods.java
//

import java.util.Scanner;

public class Methods {
	
	public static Scanner sc = new Scanner(System.in);
	
	public static void main(String[] args)
	{
		printBook();
	}

	//all methods here
	public static void printName() 
	{ 
		System.out.println("Melissa");
		printGrade();
		printLanguage();
	}
	public static void printFavorites()
	{
		printGame();
		printHoliday();
		printTV();
		printBook();
		printMovie();
	}
	public static void printBook() 
	{ 
		System.out.println("Please enter your favorite book."); 
		String favBook = sc.nextLine();
		System.out.println("Your favorite book is " + favBook + ".");
	}
	public static void printGame() { System.out.println("World of Warcraft"); }
	public static void printLanguage() { System.out.println("Java"); }
	public static void printGrade() { System.out.println("100"); }
	public static void printHoliday() { System.out.println("Thanksgiving"); }
	public static void printLeg() { System.out.println("Broken"); }
	public static void printTV() { System.out.println("Game of Thrones"); }
	public static void printMovie() { System.out.println("The Hunger Games"); }
}
