# Tax-Calculator
This is a simple web-based tax calculator application that calculates tax based on gross annual income, extra income, applicable deductions, and age group.
LINK: https://main--ubiquitous-dolphin-58b33d.netlify.app/

## Features

- Calculate tax based on input values.
- Display error messages for invalid inputs.
- Redirect to a result page with tax information.

## Files

- [`index.html`](index.html): Contains the main form for inputting tax-related information.
- [`result.html`](result.html): Displays the calculated tax information after submission.

## Usage

1. Open `index.html` in a web browser.
2. Enter the required information:
   - Gross annual income
   - Extra income
   - Total applicable deductions
   - Age group
3. Click the "Submit" button to calculate tax.
4. View the calculated tax on the result page.

## The tax calculation is based on the following rules:

-> No Taxation Under 8 Lakhs:

If the overall income (after deductions) is equal to or less than 8 Lakhs, no tax is applied.
Example:
If Gross Annual Income + Extra Income - Deductions = 6 Lakhs, no tax is applied.
If Gross Annual Income + Extra Income - Deductions = 9 Lakhs, tax is applied.

Taxation Over 8 Lakhs:

-> For income exceeding 8 Lakhs:
30% tax for individuals aged less than 40,
40% tax for individuals aged 40 or older but less than 60,
10% tax for individuals aged 60 or older.

Example:
For an individual aged 34 with an income of 40 Lakhs and no deductions:
Tax = 30% * (40 - 8) = 9.6 Lakhs.


![index_main](https://github.com/sahilbhardwaj3647/Tax-Calculator/assets/159801921/f91dc814-ae45-46f4-a7f2-61ce8d41228a)

RESULT

![index_result](https://github.com/sahilbhardwaj3647/Tax-Calculator/assets/159801921/b1a423ed-cfc2-445e-b80e-6f97b7b97103)

Also it will NOT get submitted until the AGE GROUP is selected by the user

![age_error](https://github.com/sahilbhardwaj3647/Tax-Calculator/assets/159801921/61083b49-13b1-403f-8964-c9cf35021f54)



## Technologies Used

- HTML
- CSS (Bootstrap)
- JavaScript (Vanilla JS)
