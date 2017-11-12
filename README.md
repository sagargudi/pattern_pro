# pattern_pro
how to design a rhombus pattern??? the solution is here...


import java.util.Scanner;
public class  rhombus
{
    
 
    public static void main(String[] args)
    {
             
	Scanner sc=new Scanner(System.in);
	System.out.println("Enter num : ");
	int num=sc.nextInt();	 
              System.out.print("Enter Symbol : ");
	
              char c = sc.next().charAt(0);
 
	for(int r=1;r<=n;r++)
               {
	        for(int s=1;s<=n-i;s++)
                
                        {
                               System.out.print(" ");
                        }
 
                      for(int j=1;j<=i*2-1;j++)
                
                        {
                               System.out.print(c);
                        }
	 System.out.println();
	    
               }            
               for(int r=n-1;r>0;r--)
               {
	        for(int s=1;s<=n-i;s++)
                
                        {
                               System.out.print(" ");
                        }
                      for(int j=1;j<=i*2-1;j++)
                
                        {
                               System.out.print(c);
                        }
	    System.out.println();
               }  
 
 
                
    }
}
