# Budget 2026 Android App

This project is based on the supplied Budget.xlsx workbook.

Implemented:
- Sep, Oct, Nov, Dec month tabs
- Salary, Other Incomes, Loan and total income
- Saving 1–5 with Planned and Actual amounts
- 9% interest carry-forward calculation
- Monthly budget and running expense balance
- Expense categories: Foods, Drink, Petrol, Bike, Desha, Travel, A, B, C, D, Other
- Notes/descriptions for expenses
- 2026 monthly summary and category totals
- Automatic on-device persistence (localStorage)
- Starting September data copied from the Excel workbook

## Build APK without Android Studio (GitHub)
1. Create a new empty GitHub repository.
2. Upload the contents of this folder to the repository.
3. Open the repository's **Actions** tab.
4. Run the workflow named **Build APK** (or push to main/master).
5. Open the completed workflow run and download the artifact **Budget-APK**.
6. Inside the downloaded artifact is `app-debug.apk` ready to install on Android.

The build workflow is already included at `.github/workflows/build-apk.yml`.
