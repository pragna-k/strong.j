# strong.j
import java.util.*;
public class strong{
    public static void main(String[] args){
        Scanner knnc=new Scanner(System.in);
        System.out.println("enter n value:");
        int n=knnc.nextInt();
        int i,j=0;
        int m;
        int sum,k;
        m=n;
        int fact;
        while(m>0)
        {
            k=m%10;
            fact=1;
            for(i=1;i<=k;i++)
            {
                fact=fact*i;
            }
            j+=fact;
            m=m/10;
        }
        if(n==j)
        {
            System.out.println(n+" is a Strong number");
        }
        else
        {
            System.out.println(n+" is not a Strong number");
        }
    }
}
