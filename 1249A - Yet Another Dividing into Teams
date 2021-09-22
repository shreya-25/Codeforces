import java.util.*;
import java.io.*;

public class min_teams {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int t=sc.nextInt();
        for(int i=0;i<t;i++)
        {
            int flag=0;
            int n=sc.nextInt();
            int arr[]=new int[n];
            for(int j=0;j<n;j++)
                arr[j]=sc.nextInt();
            Arrays.sort(arr);
            for(int j=0;j<n-1;j++)
            {
                if(arr[j]==(arr[j+1]-1))
                {
                    flag = 1;
                    break;
                }
            }
            if(flag==0)
                System.out.println("1");
            else
                System.out.println("2");
        }
        

    }
}
