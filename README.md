# java-test-0003-final-16431-shivani
Final Project Assignment - This repository contains the complete final project code and documentation.
```java
public class BinaryPattern {
    public static void main(String[] args) {

        int n = 6;

        for (int i = 1; i <= n; i++) {

            int num = (i % 2 == 0) ? 0 : 1;

            for (int j = 1; j <= i; j++) {
                System.out.print(num + " ");
                num = (num == 1) ? 0 : 1;
            }

            System.out.println();
        }
    }
}
```
