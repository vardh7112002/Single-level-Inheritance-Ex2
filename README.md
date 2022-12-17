# Single-level-Inheritance-Ex2

import java.util.Scanner;
public class A{
    int j=2;
   static int x=6;
    {
        j=5;
    }
  static {
        x=4;
    }

    public static void main(String args[]) {
    
    A a1=new A();
        System.out.println(A.x+"  "+a1.j);
    }
}
