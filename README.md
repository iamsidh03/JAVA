# JAVA
//Write a Java program that takes a year from user and print true if that year is a leap year otherwise print false.

import java.util.Scanner;
public class A3Q5 {
    public static void main(String[] args) {
    Scanner sc = new Scanner(System.in);
        System.out.print("Input the year: ");
        int l = sc.nextInt();
        if ((l%4==0 && l%100!=0)||(l%400==0)){
            System.out.println(l+" is a leap year: true");
        }else {
            System.out.println(l+" is a leap year: false" );
        }



    }
}
