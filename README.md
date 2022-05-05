# hashcode
Code
// Online Java Compiler
// Use this editor to write, compile and run your Java code online
public class Demo extends Object{
static int value =1; 
    public static void main(String[] args) {
         Demo d1 = new Demo();
          Demo d2 = new Demo();
            Demo d3   = new Demo();
        System.out.println(d1.hashCode()); 
System.out.println(d1.hashCode()); 
System.out.println(d1.hashCode()); 
    }
    @Override
    public int hashCode(){
        return value++;
    
    }
}
