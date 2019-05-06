# Lincoln Full-Stack Engineer Take-Home Project

## Instructions

1. Clone this repo under your own GitHub account.
2. Complete the task below.
3. After completing the task, add **hans-lincoln** as a collaborator to your cloned repo.
4. Schedule a post-project call at 

## Task 

### Background

Your client is a non-profit organization that uses, among many other channels, the services of a 3rd party vendor to solicit donations from their constituents. Every month, the vendor sends the client a CSV file of new donor information.

The CSV file is guaranteed to be well-formed. It consists of these fields:

- Donor ID*
- Donor Name
- Donor Email
- Donor Gender
- Donor Address
- Donation Amount*

Fields marked with a **\*** are required fields, and are guaranteed to be included in each row. Blank column data should be treated as **Anonymous**.

The client has requested a way to manage/visualize their donor information. They want to build a simple dashboard to:

- View all donor records
- Search records by **Donor Name**
- Filter for **Anonymous** donors
- Filter by **Donor Gender**
- Sort any column ascending/descending
- Upload any new donor CSV and have new records added

Additionally, they want to be alerted on every successfuly CSV upload with a summary that includes the following information:

- Total number of records uploaded
- Total value of donations
- Percentage of **Anonymous** donors

### Deliverables

- Build client dashboard with the above requirements
- You may use any language/framework/tool to build the dashboard. Add any relevant files/code to the cloned repository.
- Somewhere in the repo, add the public URL to view the dashboard.
- Create an alert on successful CSV upload. You may send alert to any service (email, Slack, etc), but please be prepared to demo this functionality.

### Tips

- We have provided a `donors.csv` file in the repo to use for seed data.
