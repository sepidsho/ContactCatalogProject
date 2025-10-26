# ContactCatalog

## Beskrivning
ContactCatalog är en enkel konsolapplikation i C# (.NET 8) som hanterar kontakter med Id, Name, Email och Tags.  
Programmet har meny för att lägga till, lista, söka och filtrera kontakter, samt hantera taggar.

## Hur man kör
```bash
git clone https://github.com/sepidsho/ContactCatalogProject.git
cd ContactCatalogProject
dotnet build
dotnet run
Skärmbild av körning
Dictionary<int, Contact> används för att spara kontakter med unika ID.

HashSet<string> används för att undvika e-postdubbletter.

LINQ används för sökning och filtrering.

Microsoft.Extensions.Logging används för loggning.

Tester

Testprojektet använder xUnit och Moq.
Kör tester med:

dotnet test