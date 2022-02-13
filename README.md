# use of operators
program to demonstrate operators

using System;
using System.IO;
using System.Linq;
using System.Collections.Generic;
namespace CSharp_Shell
{

	public class Program
	{
		public static void Main()
		{
			int a,b,c;
		    Console.WriteLine("enter value of a:");
			a= Convert.ToInt32(Console.ReadLine());
			Console.WriteLine("enter value of b:");
			b= Convert.ToInt32(Console.ReadLine());
			//Arithmetic operator
			Console.WriteLine("*****Arithmetic operators*****");
			c= a+b;
			Console.WriteLine("addition of two number is:" +c);
            c= a-b;
			Console.WriteLine("Substraction of two number is:" +c);
			c= a*b;
			Console.WriteLine("Multiplication of two number is:" +c);
			c = a/b;
			Console.WriteLine("Division of two number is:" + c);
			c= a %b;
			Console.WriteLine("Modulation of two number is:" +c);
		    //Relational operator
		    Console.WriteLine("*****Relational operators*****");
		    Console.WriteLine("a>b:"+(a>b));
			Console.WriteLine("a<b:"+(a<b));
			Console.WriteLine("a>=b:"+(a>=b));
		    Console.WriteLine("a<=b:"+(a<=b));
		    Console.WriteLine("a==b:"+(a==b));
			Console.WriteLine("a!=b:"+(a!=b));
            //Assignment operator
         Console.WriteLine("*****Assignment operators*****");
         Console.WriteLine("a+=b:"+(a+=b));
			Console.WriteLine("a-=b:"+(a-=b));
			Console.WriteLine("a*=b:"+(a*=b));
			Console.WriteLine("a/=b:"+(a/=b));
			Console.WriteLine("a%=b:"+(a%=b));
			//logical operators
			Console.WriteLine("*****Logical operators*****");
			bool x=true,y=false,result;
			result=x&&y;
			Console.WriteLine("AND operator: "+result);
			result=x||y;
			Console.WriteLine("OR operator: "+result);
			result=x!=y;
			Console.WriteLine("NOT operator: "+result);
		}
	}
}
