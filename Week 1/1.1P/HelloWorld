using System;

namespace HelloWorld
{
    class MainClass
    {
        public static void Main(string[] args)
        {
            Message myMessage = new Message("Hello World!");
            myMessage.Print();

            Message[] messages = new Message[4];
            messages[0] = new Message("Cool Name!");
            messages[1] = new Message("Nice Name!");
            messages[2] = new Message("Awesome Name!");
            messages[3] = new Message("That name is silly!!!!");

            Console.WriteLine("Enter Name: ");
            string name = Console.ReadLine();

            if (name == "Josh")
            {
                messages[0].Print();
            }
            else if (name == "Nick")
            {
                messages[1].Print();
            }
            else if (name == "Max")
            {
                messages[2].Print();
            }
            else
            {
                messages[3].Print();
            }

            Console.ReadLine();
        }
    }
}
