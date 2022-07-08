# KDV-Hesaplama
www.patika.dev




    import java.util.Scanner;


    public class kdv {

    public static void main(String[] args) {
        System.out.println("KDV hesaplama programi");

        double fiyat,oran1,oran2;
        System.out.println("Urun Fiyatini Giriniz");
        Scanner fiyat2=new Scanner(System.in);
        fiyat=fiyat2.nextDouble();
        System.out.println("Urun fiyati: "+fiyat);
        boolean durum=fiyat>0 && fiyat<1000;
        oran1=durum? 1.18d:1.08d;



        System.out.println("KDV Miktari: %"+ (oran1 - 1));
        System.out.println("KDV'li tutar:"+(fiyat*oran1));


    }
}
