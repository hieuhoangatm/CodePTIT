#include<stdio.h>
#include<math.h>


int giaithua(int i){
	if(i==0)
	return 1;
	if(i==1)
	return 1;
	return i*giaithua(i-1);
}
int main(){
	int n,m,k,i;
	scanf("%d",&n);
	for(i=1;i<n;i++){
		int strong=0;
	    k=i;
		while(k>0){
			m=k%10;
			strong+=giaithua(m);
			k/=10;
		}	
	    if(i-strong==0)
	    printf("%d ",strong);
    }
	return 0;	
}
