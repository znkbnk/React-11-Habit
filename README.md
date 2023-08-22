Step 1: Edit Functionality

Open the file named HabitList.js.
At the top of the file, add an import statement for the useState hook.
Within the HabitList component, use the useState hook to manage an editableHabitIndex state variable.
Create a function called handleEditClick that sets the editableHabitIndex when an edit button is clicked.
Implement a function named handleEditChange to update the edited habit's text.
Create a function called handleEditSave that resets the editableHabitIndex after saving an edit.

Step 2: Delete Functionality

Open the file named App.js.
Inside the App component, after the addHabit function, define a function named updateHabit.
Implement the updateHabit function to modify the habit at a given index.
Create a function called deleteHabit within the App component to remove a habit from the list.

Step 3: Validation and Clearing Input

Open the file named HabitForm.js.
Inside the HabitForm component, locate the handleFormSubmit function.
Add a check to ensure that the habit isn't empty before adding it to the list.
After adding the habit, reset the input field to clear it.

Step 4: Local Storage

Open the file named App.js.
Import the useEffect hook at the top of the file.
Use the useEffect hook to retrieve stored habits from local storage when the app starts.
Utilize another useEffect hook to save the habit list to local storage whenever it changes.

Step 5: Styling Enhancements

Open the file named App.css.
Replace the existing CSS rules with the provided CSS to enhance the visual appeal of your app.

Step 6: Category or Tags
Open the file named App.js.
Modify the initial habits state to include habits with associated categories or tags.
Open the file named HabitList.js.
Update the rendering of habit items to include their categories or tags alongside the habit text.
