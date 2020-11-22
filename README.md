import java.awt.*;
import java.awt.event.*;
import javax.swing.*;
import java.util.Scanner;
public class JRhyme { 
    public static void main(String[] args){

        Scanner keyboard = new Scanner(System.in);
        String noun;
        System.out.println("Enter a name:");
        noun = keyboard.nextLine();
        System.out.println("\nNursery Rhyme");
        System.out.println("\nMary had a little lamb\n" + "little lamb\n" + "little lamb\n" + "Mary had a little lamb\n" + "It's fleece was white as snow");
        System.out.println("And everywhere that Mary went\n" + "Mary went\n" + "Mary went");
        System.out.println("Everywhere that Mary went\n" + "The lamb was sure to go.");        
  }
}
