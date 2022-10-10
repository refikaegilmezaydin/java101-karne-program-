# java101-karne-program-
java 101 ilk ödevi
import java.util.Scanner;

public class KarneProgrami {
    public static void main(String[] args) {
        System.out.println("KARNE NOTU HESAPLAMA ALANINA HOŞ GELDİNİZ");
        Scanner refuj = new Scanner(System.in);
        int mt,fz,ky,tur,tar,mz;
        System.out.print("MATEMATİK NOTUNUZU GİRİNİZ:");
        mt = refuj.nextInt();
        System.out.print("FİZİK NOTUNUZU GİRİNİZ: ");
        fz = refuj.nextInt();
        System.out.print("KİMYA NOTUNUZU GİRİNİZ: ");
        ky = refuj.nextInt();
        System.out.print("TÜRKÇE NOTUNUZU GİRİNİZ: ");
        tur= refuj.nextInt();
        System.out.print("TARİH NOTUNUZU GİRİNİZ:");
        tar= refuj.nextInt();
        System.out.print("MÜZİK NOTUNUZU GİRİNİZ: ");
        mz= refuj.nextInt();
        double ort=(mt + fz + ky + tur + tar + mz);
        double son = (ort/6);
        System.out.print("TOPLAM 6 ADET DERS NOTUNUZUN ORTALAMASI: ");
        System.out.println(son);
        String krn = son>=60? "TEBRİKLER BİR ÜST SINIFA GEÇTİNİZ." : "SINIF TEKRARI YAPMAK ZORUNDASINIZ.";

        System.out.println("SINIF GEÇME DURUMUNUZ: "+krn);
        //AFERİN BANA

    }
}
