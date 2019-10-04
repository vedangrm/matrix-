# matrix-
import java.util.Scanner;


public class JavaApplication5 {

  
    public static void main(String[] args) {
       
       
      Scanner sc = new Scanner(System.in); 
        System.out.println("Enter number of rows and columns");
        int r = sc.nextInt(); 
        int c = sc.nextInt(); 
        int [][] cost  = new int [r][c] ; 
        
        System.out.println("Enter the cost matrix");
        
          for (int i = 0; i < r; i++)
          {
              for (int j = 0; j < c; j++)
              {
                  cost[i][j] = sc.nextInt();
              }
          }
          
          System.out.println("The Entered Cost table is ");
          
         for (int i = 0; i < r; i++)
          {
              for (int j = 0; j < c; j++)
              {
                  System.out.print(cost[i][j] +"\t");
              }
              System.out.println("");
          }
         
         System.out.println("Enter the Benifit matrix");
         
          int [][] benifit  = new int [r][c] ; 
        
           for (int i = 0; i < r; i++)
          {
              for (int j = 0; j < c; j++)
              {
                 benifit [i][j] = sc.nextInt();
              }
          }
          
          System.out.println("The Entered Benifit table is ");
          
         for (int i = 0; i < r; i++)
          {
              for (int j = 0; j < c; j++)
              {
                  System.out.print(benifit[i][j] +"\t");
              }
              System.out.println("");
          }
         int n; 
         do 
         {
         System.out.println("Enter the playing matrix (only `1` and `0` is accepted)");
         Sysem.out.println("Amazing"):
