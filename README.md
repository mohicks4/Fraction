# Fraction
public class fraction{

   public static int num;
   public static int den;
    
    fraction(){
        num = 1;
        den = 2;
        
        
    }
    
    public fraction(int num1, int num2){
           num = num1;
           den = num2;
        
    }
    
    public static void addition(){
        int num3 = num + den;
        
        System.out.print("Addition: ");
        System.out.println(num3);
        
    }
    
    public static void subtraction(){
        int num3 = num - den;
        
        System.out.print("Subtraction: ");
        System.out.println(num3);
        
    }
  
    public static void division(){
        
        System.out.print("Division: ");
        System.out.println(num + "/" + den);
        
    }
    
    public static void multiplication(){
        int num3 = num * den;
        
        System.out.print("Multiplication: ");
        System.out.println(num3);
        
    }
}
