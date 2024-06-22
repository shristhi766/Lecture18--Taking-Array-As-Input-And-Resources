# Lecture18--Taking-Array-As-Input-And-Resources
package arrays;
import .java.util.Scanner;
public static void main(String [] args){
      Scanner sc = newScanner(System.in)
      System.out.print("Enter the size of the array: ");
      int n = sc.nextInt();
      int arr [] = new int[n];
      for (int i = 0, i<n , i++)
      {
      System.out.println("Please enter" + (i+1) + " element: ");
      arr[i] = sc.nextInt();
      }
      System.out.print(arr[i] + " ");
      }
