# C.Code
#include<stdio.h>
int main(){
int i,j;
for(int i=0;i<8;i++){
		for(int j=0;j<8;j++){
			if((i+j)%2==0) printf("%c%c",0xa8,0x80);
			else printf(" ");
		}
		printf("\n");
	}
	return 0;
}
