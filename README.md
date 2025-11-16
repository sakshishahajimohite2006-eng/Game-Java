import java.util.*;
class Number
{
	public static void main(String args[])
	{
	Scanner sc=new Scanner(System.in);
	Random r=new Random();
	int num=r.nextInt(100)+1;
	int flag=0;
	for(int i=1;i<=5;i++)
	{
      System.out.println("guess :" +i + " :Enter your Number");
      int n=sc.nextInt();
      if(n==num)
      {
      	System.out.println("Guess is sucessful!");
      	flag=1;
      	break;
      }
  }
	
	if(flag==0)
	{
	System.out.println("Guess is unsucessful");
	System.out.println("the correct number was :"+num);
	}

  <img width="439" height="426" alt="image" src="https://github.com/user-attachments/assets/59d420ba-7f90-41b7-83d1-2d5154a9c8c1" />

	}
}
