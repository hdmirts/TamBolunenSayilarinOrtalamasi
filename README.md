```java
import java.util.Scanner;
public class ciftsayi {
    public static void main(String[] args) {
        int d; 
        int toplam = 0, count =0;
    
        Scanner inp = new Scanner(System.in);
        System.out.print("Sayıyı Giriniz :");
        d = inp.nextInt();

        for(int a =1; a <= d; a++){
            if (a%12==0){
                toplam += a;
                count++;                               
            }

        }
        System.out.println("3 ve 4'e tam bölünen sayıların ortalaması :"  + (toplam/count));
    }
}

```



