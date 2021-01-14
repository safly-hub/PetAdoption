# PetAdoptionPEDAC4JURASICPARKHW

## PEDA

\*P

> Make application that allows us to keep track of pets in pet adoption agency

      *C R U D*
      Create: *Add. (create a new pet that is available for adoption and display current features)
      Read:
      Update: *Change and Save new feature
      Delete: Old data or adopted pets

> DATABASE-PETADOPTION-ADGENCY>

    *E
      -Pet is adopted

    *Data we are working with

      *Properties*  of  P E T (CLASS)
    -Species -string
    -Gender -string
    -Age -int
    -Name -string
    -Color -string
    -Size  -string

**_M O R E P S E U D O C O D E_**

\*ALGO && \*CODE

Above Main & Under Class Program

> Static void PETS
> class PET
> {

      TO CREATE LIST AND  ATTRIBUTES/PROPERTIES
      var currentPets = new List<PET>()

> {
> //INFO FROM \*DATA
> public string Species { get ; set } -string
> public string DietType { get ; set } -string //FOR JURASSIC HW
> public string Gender { get ; set } -string
> public int Age { get ; set } -int
> public string Name { get ; set } -string
> public string Color { get ; set } -string
> public int/string? Size { get ; set }
> } >

    {

> Switch (Select.Age)
> {
> case " "
> break;
> }
> return int.Parse(Age) maybe _int.TRYPARSE?_
> }
> var PET = new PET()
> {
> Name =
> Species =
> Gender =
> Age =
> Color =
> etc =

      }

}

> Static void SummaryofcurrentPETS{DietType(property in PET<class>)} -- FOR DINO HW

> Static void IntroMessage(string welcome message)

    Console.Clear();
    Console.WriteLine("\n Welcome to Luke's Pet Adoption Agency\n")
    ConsoleWriteLine("\n Nice to see you! Let me summon my trusty guide Terence to help you today! - LUKEF$AFLYakaCEOofPETADOPTIONAGENCY\n")

CREATE BOOLEAN IF user !QUIT -- FOR P R O G R A M

var userHasChosenToQuit = false;
while (userHasChosenToQuit ==false)
{
display MENU
var choice = Console.ReadLine().ToUpper().Trim();
}

>     //Possible other features
>     // H E R E
>     // H E R E
>     // H E R E
>
> IF (choice == "quit")
> {

    userHasChosenToQuit = true;
    > *EXIT PROGRAM LOOP*

}

Static void User&PETinterface(string |)
/
/
C R E A T E - MENU (class)
Console.WriteLine("\n First lets get your first name or favorite alias\n")
Console.ReadLine();
Console.WriteLine($"\n Welcome! {alias})

    Console.WriteLine($\What would you like to do {alias})

    \*FEATURES (MENU PROPERTIES)
    Console.WriteLine("UPDATE");
    Console.WriteLine("ADOPT");
    Console.WriteLine("Put up for adoption(some of ADD)");
    Console.WriteLine("SEE -View our Pets");

    if (choice == "SEE")
    {
      foreach (var pet in Pets)
      {
        Console.WriteLine(CURRENT-PET(class) OR EACH ATTRIBUTE OF )
      }

    }

    if (choice == "Adopt")
    {
      //possibly Create Method for new property {Name}           for           PET     (class)
      *if asking for specific pet in list
        Create Boolean IF LOOP if name == "XXXTentacion"
          -Ask for PET "Name"
          Console.Write("\n Hi what is your name?\n")
          var newPet name = Console.ReadLine();
          -Console.WriteLine("\n Awesome to meet you {PetName})
      *if asking for specific pet in list to adopt
            var foundpet = pets.Find(pet => pet.Name == nameOfPet)            |
                                  |
                              in List
              pets.Remove(foundPet);
    //Ask for attributes
          -Console.WriteLine();
          -Console.WriteLine();
          -Console.WriteLine();
    ///
          -Add new PET {"Name"} to list of currentPETS (class)
          var newPet = new Pet()
          {
            Name = {name}
            Gender = {Gender}
          }
          pets.Add(newPet);
        }
    if (choice == "Update")
      Console.WriteLine("What is the Name of the pet");
      var newPet = new Pet()

      Console.WriteLine(Whatever it is we are updating)
      ReadLine -> var new size
      Update found pets size

}
