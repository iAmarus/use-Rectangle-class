public class HomeWork {

	public static void main(String[] args) {
		Rectangle rectangle1 = new Rectangle();
		Rectangle rectangle2 = new Rectangle();
		
		rectangle1.setHight(40);
		rectangle1.setWidth(4);
		
		rectangle2.setHight(3.5);
		rectangle2.setWidth(35.9);
		
		System.out.println("Rectangle 1");
		System.out.println("Width:     " + rectangle1.setWidth(4));
		System.out.println("Height:    " + rectangle1.setHight(40));
		System.out.println("Area:      " + rectangle1.getArea());
		System.out.println("Perimeter: " + rectangle1.getPerimeter());

		System.out.println("\n Rectangle 2");
		System.out.println("Width:     " + rectangle2.setWidth(35.9));
		System.out.println("Height:    " + rectangle2.setHight(3.5));
		System.out.printf("Area:      %.2f" , rectangle2.getArea());
		System.out.println("\nPerimeter: " + rectangle2.getPerimeter());
	}
}
