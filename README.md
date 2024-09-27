# Recursion-Problems
public class Factorial {
    public static int f(int n){
        
        if(n==0){
            return 1;
        }
        else{
            return n*f(n-1);
        }

    }
    public static void main(String[]args){
        int n=5; 
        int result= f(n);
        System.out.println("Factorial of" + n + "is" + result);

    }
}

