
1 / 45
Which of the following method declarations correctly declares a method named sum that takes an array of integers and returns the sum of the values in that array?
The are 1 correct answers
sum(int[] : array) : int {
  // code here
}
int sum(int[] : array)  {
  // code here
}
sum(int[] array) : int {
  // code here
}
int : sum(integer[] array) {
  // code here
}
x int sum(int array[]) {
  // code here
}




_____________________________________________________________________

2 / 45
Which of the following is a benefit of encapsulation?
The are 1 correct answers

It allows you to add functionality by extending the class.
It allows you to plug and play different components without changing the code.
It allows you the change the implementation of the internal logic without changing the API.
It allows you to couple one class with another.
x It provides code reuse.



_____________________________________________________________________
3 / 45
What will the following program print?
The are 1 correct answers

class Test {

public static void main(String args[]) {
int i=0, j = 0;

X1:
for (i = 0; i < 3; i++) {

X2:
for (j = 3; j > 0; j -- ) {

if (i < j) {
continue X1;
} else {
break X2;

}
}

}

}

System.out.println(i+""+j);

}


0 3
0 2
3 0
x3 3
2 2



_____________________________________________________________________

4 / 45
Consider the following method:

public static void ifTest(boolean flag)

{

   if (flag)   //1

   if (flag)   //2

   if (flag)   //3

   System.out.println(“False True”);

   else        //4

   System.out.println(“True False”);

   else        //5

   System.out.println(“True True”);

   else        //6

   System.out.println(“False False”);

}

Which of the following statements are correct ?

The are 2 correct answers

x If run with an argument of ‘false’, it will print ‘False False’
If run with an argument of ‘false’, it will print ‘True True’
If run with an argument of ‘true’, it will print ‘True False’
x It will never print ‘True True’
It will not compile.



_____________________________________________________________________


5 / 45
Which of the following are valid declarations:
The are 3 correct answers

int a = b = c = 100;
x int a, b, c; a = b = c = 100;
x int a, b, c=100;
x int a=100, b, c;
int a= 100 = b = c;



_____________________________________________________________________

6 / 45
You are developing a class that represents a Book. Which data type will you use for storing the ISBN number, which is an alphanumeric number, of the book?
The are 1 correct answers

int
char
x String
None of these.



_____________________________________________________________________

7 / 45
What is the result of executing the following fragment of code:

boolean b1 = false;

boolean b2 = false;

if (b2 != b1 = !b2)

{

   System.out.println(“true”);

}

else

{

   System.out.println(“false”);

}

The are 1 correct answers

x Compile time error.
It will print true.
It will print false.
Runtime error.
It will print nothing.


_____________________________________________________________________

8 / 45
What will the following code print?
List s1 = new ArrayList( );

s1.add(“a”);

s1.add(“b”);

s1.add(“c”);

s1.add(“a”);

System.out.println(s1.remove(“a”)+” “+s1.remove(“x”));

The are 1 correct answers

1 0
2 -1
2 0
1 -1
x true false


_____________________________________________________________________


9 / 45
Which code fragments will print the last argument given on the command line to the standard output, and exit without any output and exceptions on the command line if no arguments are given?
The are 3 correct answers

public static void main(String args[ ])
{
       if (args.length != 0)   System.out.println(args[args.length-1]);
}

x public static void main(String args[ ])
{
       try {      System.out.println(args[args.length-1]);        }
       catch (ArrayIndexOutOfBoundsException e) {    }
}

x public static void main(String args[ ])
{
     int i = args.length;
     if (i != 0) System.out.println(args[i-1]);
}

x public static void main(String args[ ])
{
    int i = args.length-1;
   if (i > 0) System.out.println(args[i]);
}
 public static void main(String args[ ])
{
      try { System.out.println(args[args.length-1]); }
      catch (NullPointerException e) {}
}

_____________________________________________________________________


10 / 45
Given the following code snippet:

int rate = 10;

int t = 5;

XXX amount = 1000.0;

for(int i=0; i<t; t++)

{

   amount = amount*(1 – rate/100);

}

What can XXX be?

The are 1 correct answers

int
long
x only double
double or float
float


_____________________________________________________________________

11 / 45
The JRE contains:
The are 3 correct answers

x Java API
x Java Virtual Machine
debugging tools
IDE
x Java Application Launcher


_____________________________________________________________________

12 / 45
What will the following code print when compiled and run?


import java.util.*;

public class TestClass {

    public static void main(String[] args) throws Exception {

        ArrayList<String> al = new ArrayList<String>();

        al.add("111");

        al.add("222");

        System.out.println(al.get(al.size()));

     }

}
The are 1 correct answers

It will not compile.
It will throw a NullPointerException at run time.
x It will throw an IndexOutOfBoundsException at run time.
222
null


_____________________________________________________________________

13 / 45
Which of the following are literals?
The are 3 correct answers

goto
case
break
x true
x false
x null
Integer


_____________________________________________________________________
14 / 45
What will the following code print when run?

public class Mambo {

public static String makeItBetter(String str) {

  return str+”!!!”;

}

public static void main(String args[]){

   String str = “Hi”;

   str = makeItBetter(str);

   System.out.println(str);

}

}

The are 1 correct answers

x Hi!!!
Hi
Hi!!!!!!
None of these.



_____________________________________________________________________

15 / 45
Consider the following class definition:

public class TestClass

{

   public static void main(){  new TestClass().sayHello(); }   //1

   public static void sayHello(){ System.out.println(“Static Hello World”); }  //2

   public void sayHello() { System.out.println(“Hello World “); }  //3

}

What will be the result of compiling and running the class?

The are 1 correct answers

It will print ‘Hello World’.
It will print ‘Static Hello World’.
Compilation error at line 2.
x Compilation error at line 3.
Runtime Error.


_____________________________________________________________________

16 / 45
The following code snippet will not compile…

int i = 10;

System.out.println( i<20 ? out1() : out2() );

Assume that out1 and out2 have method signature: public void out1(); and public void out2();.

The are 1 correct answers

x True
False


_____________________________________________________________________
17 / 45
What will the following code print?
String abc = “”;

abc.concat(“abc”);

abc.concat(“def”);

System.out.println(abc);

The are 1 correct answers

abc
abcdef
def
x It will print empty string (or in other words, nothing).
It will not compile because there is no concat() method in String class.



_____________________________________________________________________

18 / 45
Which of the following can be valid declarations of an integer variable?
The are 2 correct answers

global int x = 10;
x final int x = 10;
public Int x = 10;
Int x = 10;
x static int x = 10;



_____________________________________________________________________
19 / 45
Which of the following are primitive integral types in java?
The are 4 correct answers

float
nibble
x char
x byte
x short
x int
natural



_____________________________________________________________________

public class Test {

static int a;
int b;

public void incr() {

int c = a++;
b++;
C++;
System.out.println(a +  "" + b + "" + c);

}

public static void main(String args[]) {

Test test = new Test();
test.incr();
a++;
test = new Test();
test.incr();

}

}



Compilation failure.
[1 1 1
2 1 2]
x [1 1 1
3 1 3]
[1 2 1
2 3 3]
[1 2 1
3 3 3]




_____________________________________________________________________

21 / 45
Given:

What is the output?

The are 1 correct answers

public class Test {

public int div(int a, int b) throws Exception {

try {

return a / b;

} catch (ArithmeticException ae) {

System.out.println("exception in div");

return 0;
}

}

public static void main(String args[]) {

Test test = new Test();

try {

System.out.println(test.div(5, 0));

} catch (Exception e) {

System.out.println("exception in main");

}

}
}



[exception in div
exception in main]
exception in div
exception in main
x [exception in div
0]
Compilation failure
_____________________________________________________________________
22 / 45
What will be the result of attempting to compile and run the following program?

class TestClass

{

   public static void main(String args[])

   {

      boolean b = false;

      int i = 1;

      do

      {

         i++ ;

      } while (b = !b);

      System.out.println( i );

   }

}

The are 1 correct answers

The code will fail to compile because the while statement used in the code has an invalid condition expression.
It will compile but will throw an exception at runtime.
It will print 3.
It will create an infinite loop.
It will print 1.



_____________________________________________________________________
22 / 45
What will be the result of attempting to compile and run the following program?

class TestClass

{

   public static void main(String args[])

   {

      boolean b = false;

      int i = 1;

      do

      {

         i++ ;

      } while (b = !b);

      System.out.println( i );

   }

}

The are 1 correct answers

The code will fail to compile because the while statement used in the code has an invalid condition expression.
It will compile but will throw an exception at runtime.
x It will print 3.
It will create an infinite loop.
It will print 1.


_____________________________________________________________________
23 / 45
You are developing a Java rich client application that is to be installed on a lot of workstations used by the employees of your company. The users are located in various office locations across the globe. Which of the following Java technologies will be useful in delivering the application to the users over the internet?
The are 1 correct answers

Java RMI
x Java Web Start
Email
EJB and Servlet
Swing/AWT




_____________________________________________________________________

24 / 45
Which method declarations will enable a class to be run as a standalone program?
The are 2 correct answers

static void main(String args[ ]){}
public void static main(String args[ ]){}
public static main(String[ ] argv){}
x final public static void main(String [ ] array){}
x public static void main(String args[ ]){}



_____________________________________________________________________


25 / 45
What will the following program print?

class Test

{

    public static void main(String args[])

    {

        int c = 0;

        boolean flag = true;

        for(int i = 0; i < 3; i++)

        {

            while(flag)

            {

                c++;

                if(i>c || c>5) flag = false;

            }

        }

        System.out.println(c);

    }

}

The are 1 correct answers

3
4
5
x 6
7

_____________________________________________________________________

26 / 45
What will the following code print?

class Test

{

    public static void main(String args[])

    {

        int c = 0;

        A: for(int i = 0; i < 2; i++)

        {

            B: for(int j = 0; j < 2; j++)

            {

                C: for(int k = 0; k < 3; k++)

                {

                    c++;

                    if(k>j) break;

                }

            }

        }

        System.out.println(c);

    }

}

The are 1 correct answers

7
8
9
x 10
11




_____________________________________________________________________

27 / 45
What will the following program print?

class Test

{

   public static void main(String args[])

   {

      int k = 9, s = 5;

      switch(k)

      {

         default :

         if( k == 10) { s = s*2; }

         else

         {

            s = s+4;

            break;

         }

         case 7 : s = s+3;

      }

      System.out.println(s);

   }

}

The are 1 correct answers

5
x 9
12
It will not compile.



_____________________________________________________________________
28 / 45
A Java method ….
The are 2 correct answers

x cannot return multiple values.
cannot be private.
must take 1 or more parameters.
must return a value.
x must be defined inside a type definition.




_____________________________________________________________________

29 / 45
Which of these statements regarding the following code are correct ?

public class TestClass

{

   static int a;

   int b;

   public TestClass()

   {

      int c;

      c = a;

      a++;

      b += c;

   }

   public static void main(String args[]) {   new TestClass();   }

}

The are 1 correct answers

The code will fail to compile, since the constructor is trying to access static members.
The code will fail to compile, since the constructor is trying to use static member variable a before it has been initialized.
The code will fail to compile, since the constructor is trying to use member variable b before it has been initialized.
The code will fail to compile, since the constructor is trying to use local variable c before it has been initialized.
x The code will compile and run without any problems.



_____________________________________________________________________
30 / 45
What will be the result of attempting to compile and run the following class?

public class IfTest

{

   public static void main(String args[])

   {

      if (true)

      if (false)

      System .out.println(“True False”);

      else

      System.out.println(“True True”);

   }

}

The are 1 correct answers

The code will fail to compile because the syntax of the if statement is not correct.
The code will fail to compile because the values in the condition bracket are invalid.
The code will compile correctly and will not display anything.
x The code will compile correctly and will display ‘True True’.
The code will compile correctly but will display ‘True False’



_____________________________________________________________________

31 / 45
Consider the following class:

public class ArgsPrinter

{

   public static void main(String args)

   {

      for(int i=0; i<3; i++)

      {

         System.out.println(args);

      }

   }

}

What will be printed when the above class is run using the following command line:

java ArgsPrinter 1 2 3 4

The are 1 correct answers

1 2 3
ArgsPrinter 1 2
java ArgsPrinter 1 2
1 1 1
x None of these.



_____________________________________________________________________

32 / 45
What can be inserted at //1 and //2 in the code below so that it will print a number between 0.0 and 1.0?
(Assume that no package has been imported in the code.)


//1

double d = //2

System.out.println(d);

The are 2 correct answers
java.util.Random r = new java.util.Random();
and
r.random();
Random r = new Random();
and
r.random();
x java.util.Random r = new java.util.Random();
and
r.nextDouble();
Random r = new Random();
and
r.next();
x java.util.Random r = new java.util.Random(100);
and
r.nextDouble();
Random r = new Random(100);
and
r.getDouble();



_____________________________________________________________________

33 / 45
Which digits and in what order will be printed when the following program is run?

public class TestClass

{

   public static void main(String args[])

   {

      int k = 0;

      try{

         int i = 5/k;

      }

      catch (ArithmeticException e){

         System.out.println(“1”);

      }

      catch (RuntimeException e){

         System.out.println(“2”);

         return ;

      }

      catch (Exception e){

         System.out.println(“3”);

      }

      finally{

         System.out.println(“4”);

      }

      System.out.println(“5”);

   }

}

The are 1 correct answers

The program will print 5.
The program will print 1 and 4, in that order.
The program will print 1, 2 and 4, in that order.
x The program will print 1, 4 and 5, in that order.
The program will print 1,2, 4 and 5, in that order.


_____________________________________________________________________

34 / 45
Given:
int a = 5,  b = 2, c = 30;

System.out.println(a + ++b * c  );

What is the result?

The are 1 correct answers

65
210
180
x 95
Compilation failure


_____________________________________________________________________
35 / 45
Which of the following code fragments are valid method declarations?
The are 1 correct answers

void method1{ }
x void method2( ) { }
void method3(void){ }
method4{ }
method5(void){ }




_____________________________________________________________________

36 / 45
Which of the following methods do not follow JavaBeans naming conventions?

public class Bond

{

   public String ticker;

   private double Coupon;

   public String getTicker()

   {

       return ticker;

   }

   public void setTicker(String ticker)

   {

       this.ticker = ticker;

   }

   public double getCoupon()

   {

      return Coupon;

   }

   public void setCoupon(double coupon)

   {

      //do nothing

   }

   public java.util.Date getMaturity()

   {

       return new java.util.Date();

   }

   public boolean isFloater(){ return false; }

   public boolean getCallable(){ return true; }

}

The are 1 correct answers

getTicker
getCoupon
setCoupon
x getMaturity
isFloater
getCallable
All are valid.




_____________________________________________________________________

37 / 45
In the following code what will be the output if 0 (integer value zero) is passed to loopTest()?

public class TestClass

{

   public void loopTest(int x)

   {

      loop: for (int i = 1; i < 5; i++)

      {

         for (int j = 1; j < 5; j++)

         {

            System.out.println(i);

            if (x == 0) {  continue loop;  }

            System.out.println(j);

         }

      }

   }

}

The are 1 correct answers

The program will not compile.
x It will print 1 2 3 4
It will print 1 1 2 3 4
It will print 1 1 2 2 3 3 4 4
Produces no output



_____________________________________________________________________

38 / 45
What will be the result of attempting to compile and run the following program?

class TestClass

{

   public static void main(String args[])

   {

      int i = 0;

      loop :         // 1

      {

         System.out.println(“Loop Lable line”);

         try

         {

            for (  ;  true ;  i++ )

            {

               if( i >5) break loop;       // 2

            }

         }

         catch(Exception e)

         {

            System.out.println(“Exception in loop.”);

         }

         finally

         {

            System.out.println(“In Finally”);      // 3

         }

      }

   }

}

The are 1 correct answers

Compilation error at line 1 as this is an invalid syntax for defining a label.
Compilation error at line 2 as ‘loop’ is not visible here.
x No compilation error and line 3 will be executed.
No compilation error and line 3 will NOT be executed.
Only the line with the label Loop will be printed.



_____________________________________________________________________

39 / 45
Which of the following are valid declarations of the standard main method?
The are 2 correct answers

static void main(String args[ ]) { }
public static int main(String args[ ]) {}
public static void main (String args) { }
x final static public void main (String[ ] arguments ) { }
x public static void main (String[ ] args) { }



_____________________________________________________________________

40 / 45
What will be written to the standard output when the following program is run?

public class TrimTest

{

   public static void main(String args[])

   {

      String blank  = " ";  // one space

      String line = blank + "hello" + blank + blank;

      line.concat("world");

      String newLine  =  line.trim();

      System.out.println((int)(line.length() + newLine.length()));

   }

}

The are 1 correct answers

25
24
23
22
x None of the above.



_____________________________________________________________________

41 / 45
Given the following two lines of code:

int rate = 10;

XXX amount = 1 – rate/100*1 – rate/100;

What can XXX be?

The are 1 correct answers

only int or long
only long or double
only double
x int, long, float, or double
long or double but not int or float.



_____________________________________________________________________

42 / 45
Which of the following can be used as a constructor for the class shell given below?

public class TestClass

{

   // lots of code …

}

The are 2 correct answers

public void TestClass() {…}
x public TestClass() {…}
public static TestClass() {…}
public final TestClass() {…}
x public TestClass(int x) { …}


_____________________________________________________________________


43 / 45
Given the following set of member declarations, which of the following is true?

int a;    //  (1)

static int a;    //  (2)

int f( )   { return a; }    //  (3)

static int f( ) { return a; }    //  (4)

The are 2 correct answers

Declarations (1) and (3) cannot occur in the same class definition.
Declarations (2) and (4) cannot occur in the same class definition.
x Declarations (1) and (4) cannot occur in the same class definition.
Declarations (2) and (3) cannot occur in the same class definition.
x Declarations (1) and (2) cannot occur in the same class definition.

_____________________________________________________________________

44 / 45
What will the following code print when compiled and run?

public class TestClass{

   public static void main(String[] args){

        int[] arr = { 1, 2, 3, 4, 5, 6 };

        int counter = 0;

        for (int value : arr) {

           if (counter >= 5) {

               break;    

           } else {

            continue;    

           }

           if (value > 4) {

             arr[counter] = value + 1;    

           }    

           counter++;

        }

        System.out.println(arr[counter]);

   }

}

The are 1 correct answers

It will not compile.
x It will throw an exception at run time.
5
6
7
8



_____________________________________________________________________

45 / 45
Identify the fundamental principles of Object Oriented Programming.
The are 2 correct answers

x Code reuse
Dependency Injection
x Hiding unnecessary details
Scripting
Write once run anywhere (WORA)