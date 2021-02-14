# if-else-code-age-restriction-code
package com.Youtube;

import javax.xml.namespace.QName;
import java.lang.invoke.SwitchPoint;
import java.sql.SQLOutput;
import java.util.Arrays;
import java.util.Scanner;

public class Main {

    public static void main(String[] args) {

        int age=18;
        String name;
        Scanner input = new Scanner(System.in);
        System.out.println("Welcome to election office");
        //System.out.println("What is your name and age please say to me");
        System.out.println("Hi Voter, Welcome to vote center, Enter your name");
        System.out.println("Enter your name");
        name = input.next();
        System.out.println("Hi "+name+".Your name is good, Please enter your age");
        age = input.nextInt();

        if(age<18){
                 System.out.println( name +" "+ ",you are not elgible voting. You must have to minimum 18 age");
             }
             else if (age>=18){
                 System.out.println(name + " "+ " you are elgible for voting");
        }
          }

    }
