#include<stdio.h>
#include<conio.h>
#include<stdlib.h>
void main()
{
	system("color 9F"); //renk kodu
	int Anufus,Bnufus,yil=0;
	Anufus=10000000;
	Bnufus=40000000;

	while (Bnufus>Anufus) //while’in parantez içini kontrol eder uyuyorsa while’in içine girer
	{
		Anufus=Anufus+(Anufus/4); //A ülkesinin  1 yıl geçtikten sonraki nüfusunu hesaplar
		Bnufus=Bnufus+((Bnufus*12)/100); // B ülkesinin 1 yıl geçtikten sonraki nüfusunu hesaplar
		yil=yil+1;
	}
	printf("%d Yil onra A ulkesinin nufusu B ulkesinin nufusunu gecer.",yil);

	getch();

}
