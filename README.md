# learning-java
Principle of oop:-

Four major rule of object oriented programming language are as follow:-

Abstraction:-

Abstraction is the process of hiding the implementation and hiding the detail and internal detail of the process.showing only the funcationality to the user.

Example:-

For example you sending the msg you just type the text and send . you dnt knw the internal processing about the message delivery.

Example:-

abstract class Bike

{
abstract void run();

}
class Honda4 extends Bike

{

void run()
{

System.out.println("running safely..");

}
public static void main(String args[])

{
Bike obj = new Honda4();

obj.run();

}

}

2) inheritance :-

The most fundamental element of Java is the class. A class represents an entity and also defines and implements its functionality. In Java, classes can be derived from other classes
A class that is derived from another class is called subclass and inherits all fields and methods of its superclass
// A simple example of inheritance.
// Create a superclass.

class A {

int i, j;

void showij() {

System.out.println("i and j: " + i + " " + j);

}

}

// Create a subclass by extending class A.

class B extends A {

int k;

void showk() {

System.out.println("k: " + k);

}

void sum() {

System.out.println("i+j+k: " + (i+j+k));

}

}

3) Polymorphisim:-

The most common use of polymorphism in OOP occurs when a parent class reference is used to refer to a child class object.

Example:-

Class A {

Public A() {

System.out.println(“new A”);

}

}

Class B extend A{

Public B() {

System.out.println(“new B”);

}

B    b = new B();

A  a = new A();

}

4) Encapsulation:-

If a data member is private its mean it can be only access within the class .
However we use public getter and setter are used then these variables can access outside the class.
The private field and their implementation is hidden from outsidec lass.Tht’s why encapsulation is also known as data hiding.

Example:-

Public  class orange{

Private string color;

Private int size;

Public string getcolor(){

Return color;

}

Public void setcolor(string  c){

This.color=c;

}

Public  int getsize(){

Return size;

}

Public  int getsize(int s){

This.size=s;

}
