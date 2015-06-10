# 20fixes
basic problems and there fixes
public class ReversingImage {

	public static void main(String[] args) {

		int image[][] = { { 1, 2, 3, 4, 5, 6 }, { 7, 8, 9, 10, 11, 12 },
				{ 13, 14, 15, 16, 17, 18 }, { 19, 20, 21, 22, 23, 24 } };
		int reverseimage[][] = new int[6][4], len = 0;
		for (int i = 0; i < image.length; i++) {
			for (int j = 0; j < image[i].length; j++) {
				len = image.length - 1;
				reverseimage[j][len - i] = image[i][j];
			}
		}

		/*
		 * for (int i = 0; i < reverseimage.length; i++) {
		 * System.out.println(""); for (int j = 0; j < reverseimage[i].length;
		 * j++) {
		 * 
		 * System.out.print(reverseimage[i][j] + " ");
		 * 
		 * } }
		 */

	}

}
