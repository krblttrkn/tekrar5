# Ödev
* Yarıçapı **r** ,merkez açısının ölçüsü **𝛼** olan daire diliminin alanını bulan programı yazınız.
* **𝜋** sayısını 3.14 alınız.
* Formül = **(𝜋 * (r * r) * 𝛼) / 360** 
```
import java.util.Scanner;

public class Daire {
    public static void main(String[] args){
        Scanner inp = new Scanner(System.in);
        int r,a;
        double pi=3.14,alan;
        System.out.print("Direnin Yarıçapı :");
        r =inp.nextInt();
        System.out.print("Dairenin Merkez Açı Ölçüsü :");
        a = inp.nextInt();

        alan= (pi*(r*r)*a)/360;
        System.out.println("Dairenin Diliminin Alanı :"+alan);
    }
}
```