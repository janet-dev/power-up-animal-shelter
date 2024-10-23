# Paws on Heart Animal Shelter

<h2 align="left"><img src="PawsOnHeart.png"></h2>

[View the video demo on YouTube](https://www.youtube.com/watch?v=ksAsAssvfhA)

## Power Up Challenge overview

Requirements for successful completion of the [**Microsoft Power Up Program**](https://powerup.microsoft.com/):
<br><br>
Applied knowledge and skills acquired during this course which spanned across
<br>
- Dataverse
- Power Apps (Model driven apps & Canvas apps)
- Power Automate cloud flows
- Power BI reports

<br><br>
## Business Scenario (Animal Shelter)
Paws on Heart is an animal rescue charity that operates animal shelters and liaises with local families to foster animals in need. 
The goal is to help every pet to get the veterinary care they need and to find their foster families.
Project addresses these requirements using Microsoft Power Platform to streamline the operations of this organisation.
<br><br>
The organisation aims to:
<br><br>

- Improve record-keeping on animals staying at their shelters and foster homes
- Make it easier for foster families to provide support
- Provide the social media team with insightful reports to help them encourage more people to foster a pet
 
<br><br>
## The Requirements
*High-level use-cases*:
<br>
1. Create Dataverse tables and load provided data in Dataverse<br>
2. Create a model driven app listing all the animals in the shelter and their details<br>
3. Create a canvas app listing all animals available for fostering and their details<br>
4. Send Power Automate notification containing fostering process details<br>
5. Create a Power BI data visualisation dashboard
<br><br>

### Dataverse:
<br>
1. Create Dataverse tables and load provided data in Dataverse<br>
Persona: Shelter Staff<br>
Use case: to effectively manage all shelter data in one place<br>

- Import all the provided data from the Power Up Challenge resources into the Dataverse:
  - Animal data
  - Shelter locations
  - Foster family information

<br><br>

### Model-driven app:
<br>
2. Create a model driven app listing all the animals in the shelter and their details<br>
Persona: Shelter Staff<br>
Use case: to effectively manage all shelter operations<br>

- View a list of animals displaying name, type, shelter status and shelter name
- Ability to sort and filter the animal list by type of animal, by shelter status and by shelter name
- Ability to select an animal and see animal details such as name, type, age,sex, shelter status, location, medicalissues, upcoming veterinary appointment
- Ability to update the details for an animal such as medical issues veterinary information and mark an animal as “ready to foster” once they have passed their medical requirements.

<br><br>

### Canvas app:
<br>
3. Create a canvas app listing all animals, available for fostering, and their details<br>
Persona: Foster Family<br>
Use case: to facilitate choosing an animal to foster<br>

- Select a local shelter name
- View a list of animals at the selected local shelter that are ready to be fostered, featuring name, type, age, picture, and any medical conditions
- Ability to select an animal, enter foster family information and update the status to "claimed for foster“ on click of a button and the family that the animal is associated with

<br><br>

### Power Automate:
<br>
4. Send Power Automate notification containing fostering process details<br>
Persona: Foster family<br>
Use case: to advise the foster family on next steps<br>

- When an animal’s status changes to ‘claimed for foster’, send a notification email to the foster family indicating details associated with the animal and a date to arrange to come and pick up the animal.

<br><br>

### Power BI
<br>
5. Create a Power BI data visualisation report<br>
Persona: Marketing Team<br>
Use case: to showcase shelter accomplishments<br>

- Latest News (In last 1 months)
  - Number of pets who arrived at the shelter
  - Number of pets that were fostered
- Trends (In last 3 months)
  - Most rescued type of animal
  - Most fostered type of animal

<br><br>
<h2 align="left"><img src="graded.png"></h2>

## Animal Shelter Solution

<h2 align="left"><img src="docs/pictures/solution.png"></h2>

### Model Driven App
#### Shelter Details View
<h2 align="left"><img src="docs/pictures/model-view-shelter.png"></h2>
  
* Inbuilt BI report
  <h2 align="left"><img src="docs/pictures/model-bi-shelter.png"></h2>

* Add a new record
  <h2 align="left"><img src="docs/pictures/model-new-shelter.png"></h2>

  
#### Foster Familes view
<h2 align="left"><img src="docs/pictures/model-view-foster.png"></h2>
  
* Inbuilt BI report
  <h2 align="left"><img src="docs/pictures/model-bi-foster.png"></h2>

* Add a new record
  <h2 align="left"><img src="docs/pictures/model-new-foster.png"></h2>

  
#### Animals view
  <h2 align="left"><img src="docs/pictures/model-view-animals.png"></h2>
  
* Inbuilt BI report
  <h2 align="left"><img src="docs/pictures/model-bi-animals.png"></h2>
  
* Add a new record  
  <h2 align="left"><img src="docs/pictures/model-new-animal.png"></h2>

  Using a lookup
  <h2 align="left"><img src="docs/pictures/model-new-animal-lookup.png"></h2>

### Canvas App (Mobile)
#### Home Screen
  <h2 align="left"><img src="docs/pictures/canvas-screen-home.png"></h2>

  Select a shelter
  <h2 align="left"><img src="docs/pictures/canvas-screen-home-select1.png"></h2>

  Selection is filtered
  <h2 align="left"><img src="docs/pictures/canvas-screen-home-select2.png"></h2>
  
####  Detail Screen
  <h2 align="left"><img src="docs/pictures/canvas-screen-detail.png"></h2>





