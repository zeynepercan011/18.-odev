# 18.-odev

// iki say�y� birbirine b�len fonksiyon

#include<stdio.h>

int bolme(int , int);

int main(void)
{
	int a,b,sonuc;
	
	printf("1. sayiyi giriniz: %d \n");
	scanf("%d", &a);
	
	printf("2. sayiyi giriniz: %d \n");
	scanf("%d" , &b);
	
	sonuc=bolme(a,b);
	
	printf("sonuc: %d" , sonuc);
	
	return 0;
}

int bolme(int a , int b)
{

	
	if(a>b)
	{
		return a/b;
		
	}
	
	else if(a<b)
	{
		return b/a;
	}
	
	else
	{
		return a/b;
	}
	
}
