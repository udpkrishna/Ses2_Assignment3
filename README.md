package AssignmentPack;

public class Ses2Assignment3 {

	public static void printNum(int num) {
		for (int i = 1; i <= num; i++) {
			for (int j = 1; j <= i; j++) {
				System.out.print("" + j);
			}
			System.out.println();
		}
		num--;
		for (int i = num; i >= 1; i--) {
			for (int j = 1; j <= i; j++) {
				System.out.print("" + j);
			}
			System.out.println("");
		}
	}

	public static void main(String[] args) {
		Ses2Assignment3.printNum(5);

	}
}
