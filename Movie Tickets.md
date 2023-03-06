# Movie-Tickets
import java.util.Scanner;
class Theater 
{
	public static void main(String[] args) 
	{	Scanner sc = new Scanner(System.in);
		System.out.println("~~~~~~~~Welcome to INOX~~~~~~~");
		System.out.println("1. Marathi Language");
		System.out.println("2. Hindi Language");
		System.out.println("3. English Language");
		int lang = sc.nextInt();
		switch (lang)
		{
		case 1 :
			{
				System.out.println("------Marathi Movies------");
				System.out.println("1. Boys 3");
				System.out.println("2. De Dhakka 2");
				System.out.println("3. Timepass 3");
				 
				 int movie = sc.nextInt();
				 switch (movie)
				 {
				 case 1:
					 {
						System.out.println("Ticket Price is 250Rs");
				 		System.out.println("Enter Quantity of Tickets");
						int quantity = sc.nextInt();
						System.out.println("Price of Tickets is :" +quantity*250);
						break;
				 
					 }
				 case 2:
					{
				 System.out.println("Ticket Price is 200Rs");
				 		System.out.println("Enter Quantity of Tickets");
						int quantity = sc.nextInt();
						System.out.println("Price of Tickets is :" +quantity*200);
						break;
					}
				case 3:
					{
					System.out.println("Ticket Price is 180Rs");
				 		System.out.println("Enter Quantity of Tickets");
						int quantity = sc.nextInt();
						System.out.println("Price of Tickets is :" +quantity*180);
						break;
					}
				 
				 }
			}
		case 2:
				{
				System.out.println("------Hindi Movies------");
				System.out.println("1. Ligher");
				System.out.println("2. Laal Singh Tomer");
				System.out.println("3. Brahmastra ");
				System.out.println("4. Shamshera");
			
			
				 
				 int movie = sc.nextInt();
				 switch (movie)
					{
					 case 1:
						{
						 System.out.println("Ticket Price is 200Rs");
				 		System.out.println("Enter Quantity of Tickets");
						int quantity = sc.nextInt();
						System.out.println("Price of Tickets is :" +quantity*200);
						break;
						}
						case 2:
						{
						System.out.println("Ticket Price is 150Rs");
				 		System.out.println("Enter Quantity of Tickets");
						int quantity = sc.nextInt();
						System.out.println("Price of Tickets is :" +quantity*150);
						break;
						}
						case 3:

						{
						System.out.println("Ticket Price is 350Rs");
				 		System.out.println("Enter Quantity of Tickets");
						int quantity = sc.nextInt();
						System.out.println("Price of Tickets is :" +quantity*350);
						break;
						}
						case 4:
						{
						System.out.println("Ticket Price is 300Rs");
				 		System.out.println("Enter Quantity of Tickets");
						int quantity = sc.nextInt();
						System.out.println("Price of Tickets is :" +quantity*300);
						break;
						}
					}
				}
		case 3:
			{
				System.out.println("------Hollywood Movies------");
				System.out.println("1. Spider Man No Way Home");
				System.out.println("2. Doctor Strange Multiverse Madness");
				System.out.println("3. Morbius");
				System.out.println("4. Jurassic World");
			
			
				 
				 int movie = sc.nextInt();
				 switch (movie)
					{
					 case 1:
						{
						 System.out.println("Ticket Price is 300Rs");
				 		System.out.println("Enter Quantity of Tickets");
						int quantity = sc.nextInt();
						System.out.println("Price of Tickets is :" +quantity*300);
						break;
						}
						case 2:
						{
						System.out.println("Ticket Price is 250Rs");
				 		System.out.println("Enter Quantity of Tickets");
						int quantity = sc.nextInt();
						System.out.println("Price of Tickets is :" +quantity*250);
						break;
						}
						case 3:

						{
						System.out.println("Ticket Price is 350Rs");
				 		System.out.println("Enter Quantity of Tickets");
						int quantity = sc.nextInt();
						System.out.println("Price of Tickets is :" +quantity*350);
						break;
						}
						case 4:
						{
						System.out.println("Ticket Price is 300Rs");
				 		System.out.println("Enter Quantity of Tickets");
						int quantity = sc.nextInt();
						System.out.println("Price of Tickets is :" +quantity*300);
						break;
						}
				
				}
			}
				
		}

	}
}
