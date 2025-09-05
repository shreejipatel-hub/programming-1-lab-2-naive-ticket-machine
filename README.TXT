Project: naive-ticket-machine
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling
   Pearson Education

It is discussed in chapter 2.

Purpose of project: To illustrate the basics of fields, constructors, and methods.
How to start this project: Create one or more TicketMachine objects.

1)
2)the value returned by the machine after a ticket being printed is 0.
3)The machine will print the ticket no matter what.
    The machine will not give you a refund if you insert more amount that you are supposed to in the machine
4)
5)the ticket looks almost the same
     the only diffrence is that the amount on the ticket is 
     going to be diffrent compared to the other because we used diffrent price for the ticket.
6)public class Student{} and public class LabClass{} 
7)Yes. Yes the diagram is diffrent is has red lines on it.The error says "class,interface,enum or record expected".this error doesnt clearly say the
    problem with the code but it gives you a hint that the problem is with the class.
8) yes it is possible to leave out the word public from "public class TicketMachine".
9) no it is not possible to leave out the word class from the code.
10)constructor=TicketMachine
    fields=(private int balance),(private int price),(private int total) etc...
    methods=getPrice() , getBalance() , void etc...
    
11)the name because the name of the constructor is the same as the class name and a contructor does not have a return type before it.
12)count= the type is int
    representative=Student
    host=Server
13)alive
    tutor
    game
14)Student, Server, Person, Game
15)yes the order of the declaration matters. If your change the order the code will not compli the diagram will also show error and the editor will
    give that message about the syntax error.
16) yes it is necessary to add the semicolon after each statement because if you dont add a semicolon at the end the code will not compile since 
    the statement does not have an end.
17)private int status
18)it belongs to the Student class
19)2 parameters
    title= parameter=string
    price= parameter=double
20) yes it typically needs to be somewhere persistent to initalize the objects field
    the string is most probably for book's title and double for book's price.
21) public Pet(String petsName)
        {
            name=petsName;
        }
22) public Date(String month, int day, int year)
23) the one diffrence between headers is the name getBalance and getPrice
    and for the body its also the name i couldnt see any other diffrence because they are both gonna return the value at the end.
24)How much is the amount that u inserted in the machine.
25)no this means that the accessor method is independant from its field 
27)the erros that shows up is that there is not a statement
28) one of their diffrence is their return type getPrice is int and printTicket is void
29) no they do not have a return statement because they dont necessarily have to return the information for example
    insertMoney is taking money from you and to view the amount you can use the get balance button and the other one is printing a ticket.
31)/**
    * Increase score by the given number of points.
    */
    public void increaseScore(int points)
        {
            score = score + points;
        }
32)yes add credits is a mutator
33)/**
    * Reduce price by the given amount.
    */
        public void discount(int amount)
            {
                price = amount-price;
            }
34)public void setAge(int currentAge)
    {
        age = currentAge;
    }
35)public void setAlive(boolean isAlive)
    {
        alive = isAlive;
    }
36)after chnaging price=price the cost of the ticket will stay 0 because price is being equalled to itself and and the value of price before the amount
     we enter is 0 so it will stay 0.
37)it will print "My cat has green eyes.".
39)it will print "# price cents."
40) it will print the same thing as before "# price cents."
42) it is because each time a new TicketMachine is created it's an independant object and each object maintains its unique state.
43)yes it prints the same output as before.no i cant workout what  %d and %n parts mean here
44)