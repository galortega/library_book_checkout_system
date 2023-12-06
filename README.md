# Library Book Checkout System
Command line application for a library book checkout system. Continous integration Workshop.

## Stack
* Python 🐍
* Jenkins 🧪

## Description
Develop a command-line application for managing library book checkouts,
providing users with the ability to borrow books, calculate due dates, and manage return
processes.

## Requirements
1. Book Selection and Checkout
	* Display a catalog of available books with their respective details, such as title,
author, and availability status.
	* Users should be able to select multiple books for checkout and specify the
desired quantity.
2. Quantity Validation
	* Validate that the quantity entered for each book is a positive integer greater
than zero.
	* If invalid quantities are entered, the system should prompt users to re-enter
the quantities.
3. Due Date Calculation
	* Assign a standard loan period of 14 days for each checked-out book.
	* Calculate the due date based on the current date and the loan period for each
selected book.
4. Late Fee Calculation
	* Apply a late fee of $1 per day for each overdue book.
	* Provide a feature to calculate the total late fees accrued for a user's account.
5. Book Availability
	* Ensure that the selected books are available in the library inventory.
	* If an unavailable book is selected, display an error message and prompt users
to re-select the books.
6. Maximum Books per Checkout
	* Restrict users from checking out more than 10 books in a single transaction.
	* Display an error message and prompt users to adjust their selection if they
exceed the maximum limit.
7. User Confirmation
	* Before finalizing the checkout, display the selected books, their quantities, due dates, and any applicable late fees for user confirmation.
	* Users can either confirm the checkout or cancel and make changes to their
selections.
8. Return Process
	* Allow users to process book returns by entering the book details.
	* Calculate any additional late fees for overdue books returned.
9. Output
	* Provide information on the successful checkout, including due dates and any applicable late fees.
	* For return processes, display the total late fees incurred and the updated
status of returned books.
10. Error Handling
	* Handle errors gracefully and provide clear error messages for invalid inputs or any calculation errors.
	* Return a value of -1 if the input data is not valid or if the checkout process is canceled. This should only be considered as a last resort.


