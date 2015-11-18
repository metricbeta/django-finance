A simple income management application written in Python and using the Django framework. This application is designed for those running one-man consulting workshops or Micro ISV's to help keep track of income and expenses for tax-time.

## Core features ##

  * Basic income/expense management
  * Multiple-currency support (transactions in foreign currencies shown in local currency)
  * Multiple transaction types (could be seen/used as a Chart of Accounts)
  * Dashboard with recent transactions and at-a-glance view of past 12 months financial performance using Google Charts for visual display
  * Configurable financial year (eg start your Financial year in April, July, January, or whenever needed for your circumstances)
  * Income statement for any financial year or period

## Future Features ##

  * Web service exposed to allow your SAAS app to create Income or Expense lines programatically so you don't need to manually create income entries for each signup to your website

## Doesn't-Have Features ##

  * There is no balance sheet, and I'm unsure if I'll add it at this stage as it isn't needed for my situation.

## Code ##

I've been using this code for about 12 months to manage the finances for [Jutda](http://www.jutda.com.au) and it made doing my income tax return this year much easier.

A clean-up is currently being done, after which time I'll release the code in this subversion repository.