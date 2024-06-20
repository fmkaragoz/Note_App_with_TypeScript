## Note_Apps

# Vite + React + TS

This project is a simple note-taking app built with Vite, React, and TypeScript. It allows users to create, edit, and delete notes, as well as filter notes by title and tags. The app uses React Router for navigation and React Bootstrap for styling.

## Features

- Create new notes with a title, content, and tags
- Edit existing notes
- Delete notes
- Filter notes by title and tags
- Tag creation and management

## Components

### Layout

The `Layout` component is responsible for rendering the main layout of the app. It takes a list of notes as a prop and uses React Router's `useParams` to display the details of a specific note.

### NoteDetail

The `NoteDetail` component displays the details of a specific note, including its title, tags, content, and provides options to edit or delete the note.

### CreateNote

The `CreateNote` component is used to create a new note. It includes a form for entering the note's title, content, and tags.

### EditNote

The `EditNote` component allows users to edit an existing note. It pre-fills the form with the note's current title, content, and tags.

### NoteCard

The `NoteCard` component is used to display a summary of a note, including its title and tags. It also allows users to click on the card to view the full details of the note.

### MainPage

The `MainPage` component is the main landing page of the app. It displays a list of notes and provides options to filter, create new notes, and view individual notes.

### NoteForm

The `NoteForm` component is a reusable form for creating and editing notes. It includes fields for the note's title, content, and tags, as well as options to save or cancel the form.

## Hooks

### useLocaleStorage

The `useLocaleStorage` hook is used to manage local storage for storing and retrieving notes and tags.

## Types

The project includes various types such as `Note`, `NoteData`, `Tag`, `RawNote`, and `RawNoteData` to define the structure of notes and tags.

## Routing

The app uses React Router for client-side routing, allowing users to navigate between different views such as the main page, note details, and note creation/editing.

## Styling

React Bootstrap is used for styling the components, providing a clean and responsive design for the app.

This project showcases the use of modern web development tools and practices, including TypeScript for type safety, React for building user interfaces, and Vite for fast and efficient development.

## Screenshot

![Note_Apps](/public/Note_Apps.gif)
