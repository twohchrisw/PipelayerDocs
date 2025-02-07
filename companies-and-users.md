# Companies and Users

## Companies List

![Companies List](./md-images/companies-list.png)

For each company in the Pipelayer database, the Companies List will show the Company Name, the Login Id for that company, the Show in App status and the company's Parent Company if one has been set.

### Searching the list

Entering text into the Search field will instantly search the data for a company names which contain the entered text, irrespective of case.  i.e. 'WELDING' will produce the same results as 'welding'.

### Filtering the list

<img src="./md-images/companies-list-filter-buttons.png" height="40" alt="Companies list filter buttons">
<br>
<br>

| Command | Filter |
| ------- | ------ |
| All | Display all companies |
| Super Users | Display all parent companies, i.e., any company that has one or more child companies |
| Excel Only | Display any company that has 'Show in App' set to true |

### Grid Commands

At the right of each row are a set of command buttons:

| Button | Action |
| ------ | ------ |
| <center><img src="./md-images/blue-edit.png" height="30" style="color: white" alt="edit button"></center> | Edit the company details |
| <center><img src="./md-images/red-trash.png" height="30" style="color: white" alt="edit button"></center> | Delete the company (you will be asked to confirm) |
| <center><img src="./md-images/yellow-lock.png" height="30" style="color: white" alt="edit button"></center> | When enabled will prevent the user from logging in to Pipelayer Server (has no affect in the app) |

## Company Details

The company details view is displayed when an existing company has been selected from the [Company List](#companies-list) or a new company has been created.

The company details are split over several screens.

### Company Details Tab

![Company Details](./md-images/company-details.png)

| Field | Notes |
| ----- | ----- |
| Company Id | The internal database identifier [(UUID)](https://en.wikipedia.org/wiki/Universally_unique_identifier) for the company. |
| LegacyCompanyId | The company id that was used in the older Piped Server application (if applicable) |
| Show in App | When selected this company will be listed in the Company selection of the Process Details view in the Pipelayer app (for Excel technicians only) |
| Manual Testing | An app setting which when enabled will default Pressure Loss and PE Pressure Tests to manual entry rather than using a Tibiis connection |
| Viewable Job Types | |