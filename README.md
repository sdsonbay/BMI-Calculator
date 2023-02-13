# BMI-Calculator

float height, weight, bmi;

Scanner scanner = new Scanner(System.in);

System.out.println("Enter your height in meter: ");
height = scanner.nextFloat();

System.out.println("Enter your weight in kilograms: ");
weight = scanner.nextFloat();

bmi = weight / height * height;
System.out.println("BMI: " + bmi);
