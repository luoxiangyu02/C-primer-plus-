# C-primer-plus-
C++学习过程中的代码
//---------------------返回局部变量的指针（不可取）------------------
//#include<iostream>
//using namespace std;
//int * func()
//{
//	int a = 10;
//	return &a;
//}
//
//int main() {
//
//	int *p = func();
//
//	cout << *p << endl;
//	cout << *p << endl;
//
//	system("pause");
//
//	return 0;
//}
//-------------返回局部变量的引用（也不行）-----------------
//#include<iostream>
//using namespace std;
//int& ret()
//{
//	int a = 10;
//	return a;
//}
//int main(void)
//{
//	int &a = ret();
//	cout << "ret= " << a << endl;
//	cout << "ret= " << a << endl;
//	system("pause");
//	return 0;
//}
//------------------函数调用如果是别名的话，可以作为左值-------------
/*#include<iostream>
using namespace std;
int& ret()
{
	int a = 10;
	return a;
}
int main(void)
{
	int &a = ret();
	cout << "a= " << a << endl;
	*///------------------函数调用如果是别名的话，可以作为左值-------------
//#include<iostream>
//using namespace std;
//int& ret()
//{
//	 static int a = 10;
//	return a;
//}
//int main(void)
//{
//	int &a = ret();
//	cout << "a= " << a << endl;
//	cout << "a= " << a << endl;
//	ret() = 1000;
//	cout << "a= " << a << endl;
//	cout << "a= " << a << endl;
//	system("pause");
//	return 0;
//}
//	
