# SameOrNot
package stringAssignments;

import java.util.Scanner;

public class SameOrNot {
	public static void main(String[] args) {
		
    	Scanner scan = new Scanner(System.in);
    	System.out.println("Please enter any word");
    	String word = scan.next();
    	
    	if (word.charAt(0)==word.charAt(word.length()-1)) {
    		System.out.println("TRUE");
    	} else {
    		System.out.println("FALSE");
    	}
    	scan.close();
	}
}
