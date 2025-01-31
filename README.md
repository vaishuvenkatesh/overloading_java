# overloading_java
import java.util.Scanner;
public class Main{
    int age;
    String name;
    int x;
    int y;
    Main(){
        age=20;
        name="Vaishu";
    }
    Main(int a, int b){
        x=a;
        y=b;
        
    }
    public static void main(String[]args){
        Main obj=new Main();
        System.out.println(obj.age);
        System.out.println(obj.name);
        Main obj1=new Main(10,20);
        System.out.println(obj1.x);
        System.out.println(obj1.y);
    }
}
//Method overloading

public class Main{
    int regno;
    String name;
    Main(){
        regno=59;
        name="vaishu";
    }
    public static void main(String[]vais){
        Main obj=new Main();
        System.out.println(obj.regno);
        System.out.println(obj.name);
        
    }
}
