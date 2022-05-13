# Vucut-Kitle-Indeksi-Hesaplama
import java.util.Scanner;
public class Main {

    public static void main(String[] args) {

        double boy,kilo,vki;
        Scanner input = new Scanner(System.in);
        System.out.println("Lütfen boy değeri Giriniz: ");
        boy = input.nextDouble();
        System.out.println("Lütfen kilo değeri Giriniz :");
        kilo = input.nextDouble();
        vki= kilo / Math.pow(boy,2);
        System.out.println("Vücut Kitle İndeks Değeriniz:  " + vki);
    }
}
