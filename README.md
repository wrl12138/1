#include <studio.h>
int Add(int,int)
{
return x +y;
}
int Sub(int,int)
{
return x -y;
}
int Mul(int,int)
{
return x *y;
}
int Did(int,int)
{
return x /y;
}
int main()
{

do
{
int x=0;
int y=0;
int ret =0;
int input =0:
int (*Parr[5])(int,int)={NULL,Add,Sub,Did};
printf("请选择:>");
if(input>=1&&input<=4)
{
scanf("%d",&input);
printf("请选择两个操作数");
scanf("%d %d",x,y);
ret =(Parr[5])(int x,int y);
printf("%d",ret);
}
else if(input=0)
{
printf("退出程序")；
}
else
{
printf("选择错误")；
}
}while(input);
return0;
} 
