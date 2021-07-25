# java-practice-questions

Write a program to input a name(as a single character) and marks of three tests as m1, m2, and m3 of a student considering all the three marks have been given in integer format.
Now, you need to calculate the average of the given marks and print it along with the name as mentioned in the output format section.
All the test marks are in integers and hence calculate the average in integer as well. That is, you need to print the integer part of the average only and neglect the decimal part.
Input format :
Line 1 : Name(Single character)
Line 2 : Marks scored in the 3 tests separated by single space. 
Output format :
First line of output prints the name of the student.
Second line of the output prints the average mark.
Constraints
Marks for each student lie in the range 0 to 100 (both inclusive)
Sample Input 1 :
A
3 4 6
Sample Output 1 :
A
4
Sample Input 2 :
T
7 3 8
Sample Output 2 :
T
6


CODE FOR THIS QUESTION

import java.util.Scanner;

public class Solution {
    
   

	public static void main(String[] args) {
		
		/* Your class should be named Solution.
	 	* Read input as specified in the question.
	 	* Print output as specified in the question.
		*/
		Scanner scan = new Scanner(System.in);
		
		
		
		String str = scan.next();
		
		char c = str.charAt(0);
		
		System.out.println(c);
		
		
		
		
		int i = scan.nextInt();
		int j = scan.nextInt();
		int k = scan.nextInt();
		
	
        
        int avg = (i+j+k)/3; 
		
		System.out.println(avg);
		
		
	}

}
