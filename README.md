# pnr
import java.text.DecimalFormat;
import java.util.Random;
public class Random1 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub


		String  digit3="";
		for(int i=1; i<=3;i++) {
			
		 digit3 += String.valueOf(new Random().nextInt(8) +2);
		}
		
		
		System.out.print(digit3);
		double number1 =  Math.random();
		DecimalFormat numberFormat = new DecimalFormat("#");
		number1=number1*10000000;
				if(number1!=0)
					System.out.print(numberFormat.format(number1));
			 

		
}
}
