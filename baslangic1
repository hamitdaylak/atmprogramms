//CODER HAMİT DAYLAK 
//BASİT BİR BANKAMATİK PROGRAMI YAZDIM SİZİN İÇİN BANKAMATİK ŞİFRESİ ( a ) dır 
//geliştirme yapabilirsiniz for döngüsü do while döngüsü ve return dongusu kullanılmıştır
//instagram @webr00t  veya webroottr@gmail.com üzerinden bana ulaşabilirsiniz

#include <stdio.h>
#include <locale.h>
#include <conio.h>

int main()

{

	char KulAdi='a'; // kullanıcı ismi belirlenirken karakter değişkeni tanımlanır
	char dongu;//while dongüsü evet hayır sorgusunu çalıştırır
	
	
	int kart,para=1000,parola,islemsec,cekilenpara,bakiye=7000,yatirilanpara,iban,yirmilik=0,onluk=0,beslik=0,birlik=0; //para birimler için olan değişkenler
	int para1;
	system("color 4");// konsol renklendirme kodu sayılar ve harfler ile beraber yazıyordu internet üzerinden buldum 
setlocale(LC_ALL,"Turkish");// konsolun türkçe karakter içermesini sağlar 
    printf("\t |¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯¯|\n");	
	printf("\t |              CODER BANK                          |\n");
	printf("\t |              ©HAMİT DAYLAK                       |\n");	
	printf("\t |      KODDAN BANKAYA DÖKÜLEN BORSA ŞİRKETİ        |\n");
	printf("\t |             -2000-2018-                          |\n");    
	printf("\t |__________________________________________________|\n");  
	printf("CODER BANKA HOŞGELDİNİZ HERHANGİ BİR ARIZA DURUMUNDA \n\n");
	printf("0212 555 35 05 nolu numarayı arayınız kampanyalar diğer hizmetlerimiz için \n\n");
	printf("http://www.coderbank.com u ziyaret edebilirsiniz \n\n");
    printf("lütfen şifrenizi giriniz...\n\n");
    scanf("%c",&KulAdi);
    
    if(KulAdi =='a')
    {
    scanf("%c",&KulAdi);
    printf("Şifre Doğru Hoşgeldiniz \n\n\n" );
	}
    
    	else 
    	{
    		printf("şifreniz yanlış tekrardan deneyin  ");
    		return ;
    		
    		
		}
	

			do{
		system("cls"); // ekran temizlemek için yazılan kod  
		printf("hoşgeldiniz HAMİT DAYLAK \n\n\n");// ekranda isim yazar
		printf("lütfen yapmak istediğiniz işlemi sayı ile seçiniz \n");
printf("__________________________________________\n");
printf("     para cekmek icin 1 e basınız ...     |\n");
printf("     para yatırmak için 2...              |\n");
printf("     bakiye sorgulamak için 3 e basınız   |\n");
printf("     ibana para yatırmak için 4 e basınız |\n");
printf("     instagram @webr00t                   |\n");
printf("__________________________________________|\n");	
scanf("%d",&islemsec);
if(islemsec ==1)
{
	system("cls");
	printf("cekilecek para miktarını giriniz...\t\t\t");
	scanf("%d",&cekilenpara);
	{
		if(cekilenpara>bakiye) //cekilen paranın bakiyeden büyük olmaması gerektiği için bir döngü
		{
			printf("YETERSİZ BAKİYE LÜTFEN TEKRAR DENEYİNİZ \n\n\n");
		}
		else 
		{
			bakiye = bakiye - cekilenpara;
			printf("Hesabinizdan %d Tl cekilmistir.\n",cekilenpara);		
			printf("Hesabinizda toplam kullanilabilir bakiye %d TL dir.\n",bakiye);
			
		}
	}
	
	{
     
}
}
	else if(islemsec ==2)// kategori seçimi 2.secim
	{
		system("cls");
		printf("Yatırılacak Miktar giriniz \n\t");
		scanf("%d",&yatirilanpara);
		bakiye = yatirilanpara + bakiye;
		printf("thesabiniza %d TL BAKİYE BULUNMAKTADIR \n",bakiye);
		
		
	}
	else if(islemsec ==3)
	{   system("cls");
		printf("hesabinizda \t %d TL bulunmaktadır \t \n ",bakiye);
	}
	else if(islemsec ==4)
		{
			system("cls");
		printf("Göndermek istediğiniz İBAN numarasını yazınız\n\n\t");
        scanf("%d",&bakiye);		
	}
	
	
      
	  
	
    printf ("DEVAM ETMEK İSTERMİSİNİZ EVET İÇİN 'E'/ HAYIR İÇİN 'H' HARFİNE BASINIZ: \n\n\n ");
scanf (" %c", &dongu);
	}
	while(dongu == 'E' || dongu == 'e');// e harfine basınca başa saran döngü
}


