# area
just another repository
// ConsoleApplication1.cpp: 定义控制台应用程序的入口点。
//
#include "stdafx.h"
#include<math.h>
int main()
{
	double a, b, c, s,area;
	scanf("%lf,%lf,%lf", &a, &b, &c);
	s = 1.0 / 2*(a+b+c);
	area = sqrt(s*(s - a)*(s - b)*(s - c));
	printf("a=%7.2g,b=%7.2g,c=%7.2g,s=%7.2g\n", a, b, c, s);
	printf("area=%7.2f\n", area);
	return 0;
}
