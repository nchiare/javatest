# javatest
testing java


public class counter {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		int count= 0;
		int total = 0;
		
		while (count<=10) {
			System.out.printf("%d ", count);
			count++;
			
		}
		
		System.out.println();

		for (int i = 0; i<=10; i++) {
			System.out.printf("%d ", i);
		}

		System.out.println();
		
		for (int i = 2; i<=20; i+=2) {
			
			total+=i;
		}
		System.out.printf("The sum is %d", total);
		
	}
	
	
}
