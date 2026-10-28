# Pet Adoption Center MVC Project

This is a beginner ASP.NET Core MVC project about pets and adoption applications.

Models: `Pet`, `Shelter`, `Adopter`, and `AdoptionApplication`.

Relationships:

- One shelter can care for many pets.
- One pet can have many adoption applications.
- One adopter can submit many adoption applications.

The controllers use `Include` so related shelter, pet, and adopter names appear in the pages.

Open `pet project.slnx` in Visual Studio, build it, run `Update-Database` if needed, and then run with Ctrl+F5. Create a shelter and an adopter before creating a pet or adoption application. The database is named `PetAdoptionDb` in SQL Server LocalDB.

