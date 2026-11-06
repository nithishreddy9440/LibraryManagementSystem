# LibraryFlow - Online Library Management System

React + Vite academic project for Front End Development Frameworks.

## Requirements implemented

- React + Vite project structure with production build script.
- Admin and Library Member modules.
- Login and signup using browser Local Storage.
- Role selection during signup: Administrator or Library Member.
- Admin dashboard, book catalog, member directory, QR registration, issue/return, reports and settings.
- User dashboard, searchable book catalog, availability checking, borrowing, reservations, My Loans and My Reservations.
- Book, loan, reservation, member and account data persist in Local Storage.
- Search and category filtering for books.
- Search for members and borrowing records.
- Add-book and add-member forms with validation.
- Responsive UI and light/dark mode.
- Vercel SPA rewrite configuration included in `vercel.json`.

## Run locally

```bash
npm install
npm run dev
```

Open the local Vite URL shown in the terminal.

## Production build

```bash
npm run build
npm run preview
```

## Demo flow for review

### Administrator
1. Create an account and choose **Administrator**.
2. Open Overview.
3. Add a book from Book Catalog.
4. Add a member from Members.
5. Search/filter books.
6. Issue and return a book.
7. Open QR Registration.
8. Open Reports and Settings.

### Library Member
1. Log out and create another account as **Library Member**.
2. Open Browse Books.
3. Search for a title and check availability.
4. Borrow an available book.
5. Reserve a book.
6. Open My Loans and My Reservations.
7. Return a borrowed book.

## Deployment

Import the project into Vercel. The included `vercel.json` provides the SPA rewrite so client-side navigation works after deployment.

## Important academic note

Local Storage is used for demonstration and coursework only. It is not a secure production authentication/database solution.

## Review 02 UI Updates
- Separate Admin and Student login flows
- Working Profile page with editable name and saved Local Storage session
- Quick Guide modal for Admin and Student workspaces
- Dashboard thought-of-the-day / reading-thought cards
- Admin dashboard Quick Tools: QR Registration, Quick Registration, Issue & Return, Reports
- Student dashboard Library Uses cards and My Profile shortcut
- QR Registration page includes QR code, print poster, copy link, and quick member registration
# LibraryManagementSystem
