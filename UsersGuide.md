# Introduction

![](img/intro4.png)  
The _Information Management and Innovation to Protect Children in Emergencies_ project has developed a software application that will help partners securely collect, store, manage, and share data for protection-related incident monitoring and case management. The new platform is called _Primero_ \(Protection-related Information Management\). _Primero_ supports multiple modules, including the “next generation” of the field-tested, inter-agency CPIMS and GBVIMS systems, which are currently in use in 20+ countries. These new iterations, called the CPIMS+ and GBVIMS+, can operate separately or be deployed as integrated modules on the _Primero_ platform. The inter-agency Steering Committees that govern the use of each of these modules will continue to support the new system.

![](img/v2/case-list-intro.png)

_Primero_ is flexible and adaptable to accommodate a broad range of protection concerns including GBV, unaccompanied and separated children, and monitoring grave violations of children’s rights in situations of armed conflict. To meet operational challenges, the application was designed to function both on- and off-line, with limited or no connectivity, and in multiple deployment configurations. A strong emphasis has been placed on security and confidentiality, with intuitive workflows designed to simplify processes while promoting good practice. Role-based access and granular security ensures that only those who need to see data will have access to it. All system transactions are time stamped, password protected and encrypted. _Primero_ has a user-friendly interface and intuitive tools, facilitating the work of field personnel while decreasing security risks and duplication. Primero functions as a Progressive Web Application (PWA), which meanssome functionality, such as basic information collection, still work when the user is offline. In addition to exports in a number of formats, Primero has a highly secure application program interface \(JSON API\), which facilitates interoperability with other systems.

_Primero_ functions as a distributed database, meaning that implementing partners can retain ownership of data while contributing and sharing information on shared programmes. In child protection interventions, referrals and case transfers are critical to effective service provision. Sharing sensitive information is a part of good programming. Data exchanges between organizations should be governed by endorsed information sharing protocols adapted to local contexts. _Primero_ design is based on the “need to know” principle; it does not impose data sharing, but facilitates the process when consent is provided, and when it is deemed appropriate and safe by partners.

Good information management practice emphasizes the importance of making data actionable. _Primero_ has built-in customizable reports that can facilitate periodic reporting processes, and be used to analyze data for programmatic insights. A document and photo repository allows end users to organize relevant resources in one convenient place.

>  _A note for end users. Although there are a standard set of forms configured in the CPIMS+ based on the CPWG standard forms that we recommend using, your System Administrator may have configured these forms specific to your location and needs. For any questions about the forms and information you have or need, please reach out to this person. To find contact information for your system administrator, please click the "Support" link in the navigation menu of Primero_

## Logging In

When logging into Primero, you’ll see Username and Password boxes. Click in the Username box and type in the unique user name provided to you by your System Administrator. Then enter your password in the field below and click on 'LOG IN'.

![](img/v2/login.png)

# Navigating Primero

## Navigation Menu

The Navigation Menu appears at the left side of your screen. You can access this menu from any page of the app.

![](/img/v2/side-navigation-bar-page.png)

On smaller devices, such as tablets or phones, you will need to click or tap on the menu button to show the Navigation Menu. The menu button will appear at the top left of your screen.

![](/img/v2/mobile-case-list.png)

![](/img/v2/mobile-nav-menu.png)

TODO Adjust screenshots

## Dashboard

The Dashboard is where you can quickly find information about the records you manage in Primero. The type of information that appears here will depend on the type of work you do for your organization. For instance, social workers, managers, and agency administrators will each see dashboards which are tailored to the needs of their day-to-day work.

A few notes about dashboards:
- You can always get back to the dashboard by clicking on the "Home" link in the Navigation Menu. 
- Clicking on any of the numbers in the dashboard sections below will take you to a list of the records which that number represents.
- In general, numbers in the dashboard represent records to which you have access. For example:
	- If you have access to only your own cases, numbers in the dashboard will reflect only those cases which you manage directly, or which have been referred to you.
	- If you are a manager and have access to all the cases managed by users in your team (user groups), the numbers in your dashboard will reflect these cases.
	- Administrator dashboards generally reflect all records in the system.
- Dashboard numbers also tend to represent only open records. Unless the dashboard explicitly mentions closed records, assume that it represents only open ones.
- Dashboard numbers also exclude disabled records.

### Case Worker Dashboards

The image below shows an example of the dashboard you might see as a case worker when you first login to Primero.

![](/img/v2/dashboard-cp-cw.png)

- *Cases by Assessment Level* - This section tells you how many of your cases are at each "Assessment Level" (sometimes also called "Risk Level")
- *My Cases* - This includes two indicators:
	- "Total" - The total number of cases you manage
	- "New and Updated" - A case is included in this number if 1.) a supervisor has just assigned it to you; or 2.) another user in the system has added information to the case since the last time you saw it.
- *Shared with Me* - This shows you the number of cases which have been referred or transferred to you. We will review referrals and transfers in a later section.
- *Shared with Others* - This shows you how many of your cases have been referred or transferred to someone else in the system. We will review referrals and transfers in a later section.
- *Approvals* - This tells you how many of your approval requests are pending, approved, or rejected. Each type of approval appears with its own column.
- *Workflow - Individual Cases* - This tells you how many of your cases are at each stage of the case management workflow. Please note that different implementations may use different specific workflow stages.

![](/img/v2/dashboard-cp-cw-workflow.png)

Please note that these dashboard sections are only meant to serve as an example. The exact dashboards you see when you login will depend on your Primero implementation's configuration.

### Manager Dashboards

Below are some examples of sections which may appear in your dashboard if you are a manager.

![](img/v2/dashboard-cp-mgr-1.png)

- *Cases by Assessment Level* - See description above.
- *My Group's Cases* - This shows the total number of open and closed cases managed by all of the case workers in your team.
- *Shared with Me* - See description above. Note that, because the user in the example is not able to receive referrals, they only see information on the number of cases which other users have transferred to them, and which still have not been accepted. We will discuss referrals and transfers in a later section.
- *Shared with Others* - See description above.

![](img/v2/dashboard-cp-mgr-2.png)

- *Shared from My Team* - This is similar to the "Shared with Others" section, except that it shows how many of the cases managed by each of the case workers in your team have been transferred or referred to other users.
- *Shared with My Team* - This is similar to the "Shared with Me" section, except that it shows how many of the cases other users have referred or transferred to case workers in your team.

![](img/v2/dashboard-cp-mgr-3.png)

- *Overdue Tasks* - For each case worker in your team, this section shows how many cases have a task which is past its due date. This is broken down by the four type of task: Assessment, Case Plan, Service, and Follow Up.

![](img/v2/dashboard-cp-mgr-4.png)

- *Workflow - Team Cases* - For each case worker in your team, this section shows how many cases are at each stage of the case management workflow. Please note that different implementations may use different specific workflow stages.

### Admin Dashboards

The below image gives an example of the sections you may see in your dashboard if you are an administrator.

![](img/v2/dashboard-cp-admin.png)

- *Cases by Location* - This table shows the number of cases registered in each location. For each location, the table also shows:
	- "Open Cases" - Total number of open cases registered in this location
	- "New (Last Week)" - Cases registered in this location 7-14 days ago.
	- "New (This Week)" - Cases registered in this location 0-7 days ago.
	- "Closed (Last Week)" - Cases registered in this location which were closed 7-14 days ago.
	- "Closed (This Week)" - Cases registered in this location which were closed 0-7 days ago.
- *Cases by Protection Concern* - Shows the number of cases with each type of protection concern, broken down by:
	- "All Cases" - This includes both open and closed cases.
	- "Open Cases" - This includes only cases which are still open.
	- "New (This Week)" - Open cases registered 0-7 days ago.
	- "Closed (This Week)" - Cases which were closed 0-7 days ago.

## Audit Logs

Some administrative users and team managers may have access to the *Audit Logs*. To access this feature, click the Settings link in the Navigation Menu. Once you are in Settings, click "Audit Logs" in the Settings Navigation Menu.

![](img/v1-6/image1.png)
![](img/v1-6/image2.png)

The Audit Logs page shows you a list of all actions which users have committed in the system. Each row represents a different action, including the username of the user, the type of action, the type (and sometimes the ID) of the record on which the action was performed, and the date and time of the action. Using the filters menu to the right of the list, you can limit which audit log entries are displayed. You can filter by date and time or username. To apply a set of filters, click "Apply," and to clear out all filters, click "Clear."

![](img/v1-6/image3.png) 

NOTE: The Audit Logs do not contain identifiable information from records. For instance, an audit log entry might tell you that the user "john-case-worker" edited a case with the ID "abcd123" at 10:15 on October 1, 2020. However, it will not tell you what specific information was added to the case.

## Tasks List

If you click on the "Tasks" link in the Navigation Menu, you will arrive at the **Tasks** page.

![](img/v2/tasks-view.png)

Here, you will see the incomplete Tasks present for all of the cases you manage. Primero automatically generates Tasks for four types of actions: assessments, case plans, services, and follow ups. For each Task, the list shows:
- Case ID
- Name of the Case
- Priority Level (also sometimes called "Risk Level" or "Assessment Level").
- Type of Action
- Due Date
- Status (either "Overdue" or "Almost due")

Primero automatically generates Tasks based on information you fill out in the Case forms. Each type of Task action has a date field in the Case forms that acts as its due date. As soon as a user enters a date value into one of these fields, Primero generates a Task with that due date. To find out which field sets the due date for a Task, hover over the due date for any Task you find in the Tasks page.

TODO Screenshot

Each type of Task action also has a date field in the Case forms which marks the Task as "complete". Once a user enters a date value into this field, the Task is marked as "complete" and disappears from the Tasks list.

To complete a Task, click on that Task in the list. You will arrive at that Task's Case, on the form which corresponds to that Task and contains its "complete" field. (Note: Usually the "complete" field for a Task will have help text to let you know it is used to complete a Task.) For example, if I click on a Case Plan Task, I will arrive at the Case Plan form for that Case. This form contains the field "Case Plan Initiated". If I fill out this field, the Task will be marked as "complete."

TODO Screenshot

Note that each Primero configuration may have different names for the fields which set and complete Tasks. Below is a list of the fields used for each type of Task action in the Primero default configuration.

- Assessment
	- Due Date: "Date Assessment Due" on the "Basic Identity" form.
	- Complete: "Assessment requested on" on the "Assessment" form.
![](img/v2/assessment-due.png)

- Case Plan
	- Due Date: "Date Case Plan Due" on the "Assessment" form.
	- Complete: "Date Case Plan Initiated" on the "Case Plan" form.
![](img/v2/case-plan-due.png)

- Service:
	- Due Date: "Implementation Timeframe" on the "Services" subform.
		- NOTE: Each Service subform entry will generate its own Task.
		- NOTE: "Implementation Timeframe" is a dropdown, not a date field. In some configurations, the "Appointment Date" field is used to set the Task due date instead.
	- Complete: "Service Implemented On"

![](img/v2/services-due.png)

- Follow Up:
	- Due Date: "Follow up needed by" on the Follow Up subform
		- NOTE: Each Follow Up subform entry will generate its own Task.
	- Complete: "Follow Up Date" on the Follow Up subform.

![](img/v2/followup-due.png)

## Record Lists

There are three main types of records in Primero: **Cases**, **Incidents**, and **Tracing Requests**. In the Navigation Menu, below the Tasks link are the links to the List pages for each type of record. These are the **Case List**, the **Incident List**, and the **Tracing Request List**. Depending on the work you do for your organization, you may only have access to one or two of these pages. For instance, in most Child Protection contexts case workers only deal with Cases, and so only have access to the Case List. For this reason, we will use the Case List to explain how the record list pages work.

![](img/v2/case-list-view.png)

## View and Edit a Record

In the Case List, you can click on any Case to see more details. You will arrive at the View Case page. On this page, you can only _view_ information about the case; you cannot _edit_ it. In order to edit information about the case, click the "Edit" button with the pencil icon at the top right of the page.

![](/img/v2/edit-case.png)

You should now be able to update information about the case. Once you have made changes, click the **SAVE** button in the header. NOTE: If you do not click the Save button, your changes will be lost.

![](/img/v2/save-case.png)

### Workflow Status Bar

On the view and edit pages for a Case, the user will see the **Workflow Status Bar**. This tells the user which stage of the case management workflow the case has reached. 

While each configuration will have its own specific workflow statuses, the default Primero configuration has the following:
- **New** - When the case is first created it gets this status by default.
![](img/v2/workflow-new.png)
- **Assessment** - This status is set when the user records a value for the "Assessment requested on" field on the Assessment form.
- **Case Plan** - This status is set when the user records a value for the "Date Case Plan Initiated" field on the Case Plan form.
- **Service Provision** - If the user adds an entry to the Services subform, this status gets set.
	- NOTE: In some configurations, services are categorized by "Response Type". In these configurations, the "Service Provision" status is split into multiple statuses - one for each "Response Type" option. The case gets the status which corresponds with the Response Type of the service which the case worker added most recently. For instance, if a case worker refers the case to a service provider for a service with a Response Type of "Immediate Response", the workflow status will also be "Immediate Response."
![](img/v2/workflow-update.png)
- **Closed** - This status is applied when a user performs the "Close" action on a Case.
- **Reopened** - This status is applied when a user performs the "Reopen" action on a Case. In this situation, the "Reopen" status appears where the "New" status normally appears in the Workflow Status Bar. This indicates that the case management workflow has started from the beginning.

## Flag Button

## Action Buttons

To the right of the "Edit" button on the View Case page, you should see a small button with three dots. This is the **Actions** button.

![](img/v2/action-menu-collapsed.png)

![](img/v2/action-menu.png)

The actions, depending on your permissions, are:

- Refer
- Assign
- Transfer
- Close / Reopen
	- Note: This action will appear as "Close" if the Case is open, and "Reopen" if the Case is closed.
- Disable / Enable
	- Note: This action will appear as "Disable" if the Case is enabled, and "Enable" if the Case is disabled.
- Request Approval
- Approvals
- Export

NOTE: When using these actions, you must follow the your local Standard Operating Procedures (SoPs). Primero  does not replace normal day-to-day communications (e.g. email, text, WhatsApp) between the people and organizations that perform Child Protection work.

## Language Toggle 

At the bottom of the Navigation Menu, you will see a dropdown with a small globe icon and the your current language. This is the **Language Toggle**. Click this to view Primero in a different language.

![](img/v2/language-menu.png)

![](img/v2/language-menu-detail.png)

![](img/v2/language-ar.png)

## Support

In the Navigation Menu, below the Exports link, you should see the **Support** link. Clicking on this will bring you to page with contact information for your system administrator, as well as links to support forums and documentation.

TODO Screenshot

## My Account and Password Change

In the Navigation Menu, below the Support link, you will see a link with your username. Click this to go to the **My Account** page.

![](img/v2/my-account.png)

Here, you can see details about your user account. Click the Edit button at the top right of the page to update any of these details or to change your password.

![](img/v2/my-account-edit.png)

Here, you will be able to update the following:

 * **Full Name**: The name managers and administrators will see when looking at your account.
 * **User Code**: Depending on configuration, may impact composite ID field generated for records you create. This is not often used.
 * **Password**: Must be at least eight characters and contain both letters and numbers.
 	* To update your password, please click the "Change Password" link. Otherwise, your password will stay the same.
 * **Language**: This will be the default language in which you will see the application.
 * **Phone**: Allows other users with the ability to view your profile to contact you.
 * **Email**: Will be used for any email notifications.
 * **Services**: Any services you will be providing through Primero. This will determine whether and when you appear as a potential recipient for record referrals.
 * **Position**: Your official title within your organization.
 * **Current Location**: The location where you are always or most-often based. This will determine whether and when you appear as a potential recipient for record referrals and transfers.
 * **Receive email notifications**: Will determine whether you receive email notifications, including the following:
   * Cases assigned, transferred, or referred.
   * Requests from other users for you to transfer one of your cases to them.
   * Manager approvals and requests for manager approval.

![](img/v2/my-account-save.png)

Click the **SAVE** button once you are finished making changes.

# Filtering

Filtering your Case List or search results is an efficient way to narrow down to the case or cases that need your immediate attention. You can filter the list to show not only if a case has other characteristics but contains specific information within those characteristics as well. For example, you can filter by males only, but you can also filter by specific Protection Concern, Current Location, and the case registration date range.

The Filter panel is visible on the search results page or when you click **CASES** tab in the header. See below:

![](img/v2/filter-cases-cp.png)

In the image, there is the normal checkbox filter selection, in which you click using your mouse, but also date range and drop down fields. For Date Ranges, you can enter these using any of the date field type actions. You can set the range for one day as well. Drop down fields in the filters panel are clickable with the mouse and only allow you to select one value at a time.

Once you have selected one or more filters (e.g. Female cases with ages between 0 and 5), you can apply them to the case list. To do this, simply click the "Apply" button at the top of the filters panel.

You can also save a set of filters for later use by clicking the "Save" button, positioned next to the "Apply" button. This will take you to the modal pictured below.

![](img/v2/filter-save.png)

Here, you enter a name for this new saved search. In this case, we have entered the name "Girls between the age of 0 and 5." Click "Save" to save the search. Once the search has finished saving, click on the "Saved Searches" tab in the filters panel.

![](img/v2/filter-saved-list.png)

Here you see the search you had saved earlier. If you click on it, you'll notice that the filters you had previously selected have been applied to the case list. To delete a saved search, you can click on the 'x' next to the search's row in the "Saved Searches" tab.

# Flagging

Flagging a case is a way to alert either yourself or a manager that a case needs additional work or attention. To flag a case:

 1. Once you have opened the case, click on Flags
 2. Enter the flag reason and if applicable the Date by which this flag
    needs to be addressed
 3. Click flags to complete

![](/img/v2/flags-button.png)
![](/img/v2/flags-new.png)

Note that only the person who flagged the case can unflag the case. To do so:

 1. Click on the (+) button next to the flag, under the Unflag Case heading.
 2. Enter a reason for unflagging the case.

A history of the flags and unflags for the case is stored. To see the history, click on the View History tab, you can view the details of the flags and unflags.

![](/img/v2/flags-list.png)

# Reopen

Users have the ability to reopen closed cases. Reopen displays in the Action menu on the case view page below Disable; it does not display on the case list view . Clicking Reopen brings up a confirmation dialog saying that clicking ok will change the status of the case to open. When the user clicks OK, the “Case Reopened?” field in the **Basic Identity** form is checked, the case status is set to Open, and the case’s state is set to Valid. This also creates an entry on the **Record Information** form.

![](/img/v2/reopen-case.png)

# Approvals

## Caseworker

Case worker roles have the ability to request approval for a case plan, BIA, or closure from the manager. This is done by going into the ACTIONS button dropdown, clicking on "Request Approval," and then clicking on the type of approval you would like to request. This will produce a modal to submit the request.

![](/img/v2/approval-button-cw.png)

If you request a case plan approval, the below modal will appear. Select a case plan type \(the options will correspond with the various response types\) and then click "OK."

![](/img/v2/approval-request-cw.png)

The modal for requesting closure approval will be similar, except that it wil not have a dropdown for case plan type. Here, simply click "OK" to request approval.

Once the approval request is made, it will show up as pending under the approvals section on the caseworker dashboard. It will also appear on the manager’s dashboard as a pending approval. Once the manager approves or rejects the form for the case, the status will change on both the case worker and manager dashboards.

All approvals for a case will also appear in the **Approvals** form section on the case edit and view pages. Here, you will see the type of approval (case plan or closure), the approval's status, the date of the approval request, and, if the approval is for a case plan, the type of case plan.

![](/img/v2/approvals-status-cw.png)

## Managers

Managers may have the ability to approve a case's case plan and/or closure, depending on configuration. To check to see if any approvals have been requested for a case, a manager can go to the **Approvals** form on the case view page (pictured above). As you can see, an entry for an approval in the forms will tell you what type of approval it is (BIA, Case Plan or Closure).

To perform an approval, go into the ACTIONS button dropdown, click "Approvals," and then click either "Approve Case Plan," "Approve Closure," or "Approve BIA," depending on the type of approval. You will see a modal like the one pictured below. To complete the approval, simply click the "Yes" check box, add in any necessary comments, then click "SUBMIT."

![](/img/v2/approval-button-mgr.png)

![](/img/v2/approval-mgr.png)

# Manager Notes

Managers overseeing a team of case workers may want to add notes to a particular case so that they can give the case worker guidance on case management. When viewing a case, managers should see a button marked "Add Notes" at the top of the page.

![](/img/v2/notes-mgr.png)

Click this button. A modal will appear. Here, you can write the subject of your note, as well as its full text. Click submit to add the note to the case.

![](/img/v2/notes-add-mgr.png)

When the case worker logs in and views this case, a notification will appear on the form tab for the Notes or "Other Comments" form.

![](/img/v2/notes-alert-cw.png)

If the case worker then clicks on the form, they will be able to see the manager's note, including the subject, full text, the manager's username, and the date the note was added.

![](/img/v2/notes-view-cw.png)

Case workers will also see a notification about the new note when viewing the case on mobile as well. For more information on this, please see the **Primero Mobile User Guide**

# Create Incident from Case

When viewing a GBV case, a case worker can create an incident directly from the case by clicking the "CREATE INCIDENT" button, located next to the ACTIONS button in the **Anchored Header**. Doing so will re-direct the user to the create incident form, with case information automatically loaded into the **Survivor Information** form.

![](/img/image87.png)

Alternatively, a user--depending on configuration--can create an incident from any case from the case list or search results views. To learn more about this capability, read the section labeled "Adding Incident to Case from List View".

# Search and Advanced Search

## Quick Search

Quick Search refers to the search field in the header navigation bar. From here you can type in your search and return a list of possible matches. If you are searching from the cases page you can enter your case’s value for one of the following fields to find a match: “Long ID,” “Case ID,” “proGres ID,” “Name,” “Nickname,” “Other Name,” “Ration Card Number,” “ICRC Ref No.,” “RC ID No.,” “UNHCR ID,” “UN Number,” “National ID Number,” “Number of Other ID Document,” and “Other Agency ID.” When looking for a tracing request, you can search these fields: “Long ID,” “Inquirer ID,” “Name of inquirer,” and “Nickname of inquirer.” After searching, you can filter results further.

## Searching for Records Owned By Other Users

Depending on your configuration, some users may have the ability to search for records owned by other users. In this case, the records are only visible in the list view. Clicking on a record in this view does not take the user to the view page for that record. Instead, the user can perform actions on the record from the list view.

![](/img/image88.png)

To do this, go to the record list page, and search for your record using an id or other searchable field. Once your search results appear, select the check box for the record on which you wish to perform an action. Now, select the action you wish to perform in the action button dropdown.

![](/img/v1-6/image4.png)

## Viewing Record Details

Before performing an action, you may wish to see some information about the record you have selected, even if you do not have permission to see all of the record's information. Some users will have permission to see a limited set of attributes for other users' records, using what is known as the *View Details* modal. To see information on such a record, click on the "View" link at the right-hand side of the record's entry in the list. You will then see a modal containing information on the case.

![](/img/view-details-link.png)

![](/img/view-details-modal.png)

Depending on your user's role configuration, you may be able to see the case's photo in this modal. The permission to view this photo is different from the one which allows you to see the *View Details* modal. For more information on configuring user roles, please see the **Primero Administration Guide**.

## Adding Incident to Case from List View

Depending on your configuration, a user may be able to add an incident to a case from the list view or when searching for a case. To add an incident to a case, select your case's check box on the search results page, then, under the action button dropdown, select "Add Incident." You will see the following modal. Here, enter information on the incident you are adding, and then save.

![](/img/image89.png)

Depending on your user's configuration, you may also see a second button, marked "Save and Add Service Provision." Clicking on this will save the incident details you have entered and then take you directly to the add service modal, where you can enter information on a service rendered for the child.

![](/img/v1-6/image12.png)

## Adding Service Provision to Case from List View

Depending on your configuration, a user may be able to add a service provision to a case from the list view or when searching cases. To add a service to a case, select your case's check box on the search results page, then, under the action button dropdown, select "Add Service Provision." You will see the following modal. Here, enter information on the service you are adding, and then save.

![](/img/image102.png)

## Searching for Duplicate Cases

Depending on your role permissions, you may have the ability to search in the system for potential duplicate Cases. To perform a Duplicate Search, click on the **DUPLICATES** link in the navigation bar.

![](/img/duplicate-search-intro.png)

Here, using the search criteria on the right side of the page, you can search to see if a child has an existing Case in the system. The criteria here are the same ones used to perform matching between Cases and Tracing Requests. For more information about Matching Criteria, please see the **Primero Administration and Configuration Guide**. 

In the example below, we are searching for a 12-year-old Iraqi boy with the name "Mohamed."

![](/img/duplicate-search-criteria.png)

Click the **SEARCH FOR DUPLICATES** button to see your search results.

![](/img/duplicate-search-results.png)

The results that appear will include likelihood scores of "Possible" or "Likely." For more information on how scoring works, please see the **Scoring** section.

To see some limited details about a case, click the "View" link next to it.

![](/img/view-details-modal.png)

# Exporting Information on Records

Exporting individual cases or a list of cases can be useful in a number of ways. This action can be found in the **ACTIONS** header button which   will display a drop down to select what format you want to export - PDF, XLS, CSV, etc.

| **Format** | **Description** | **Fields Included** |
| --- | --- | --- |
| CSV | Stands for “Comma-Separated Values.” Readable in excel, and can be imported back into any Primero instance. | All fields to which the user’s role has access. |
| Excel | Exports to a standard .xls file, which can be re-imported back into Primero. | All fields to which the user’s role has access. |
| JSON | Easiest format to be read \(only\) by Primero, and the preferred format for importing. | All fields to which the user’s role has access. |
| Photo Wall | Exports a PDF file with the photo of each selected case along with the case’s ID. Cannot be re-imported into Primero. | Photo, ID. |
| PDF | PDF file containing a profile on each case, including the fields from the forms specified by the user. Cannot be imported. | All fields specified by the user, to which the user’s role has access. |
| UNHCR | CSV file specifically formatted to be compatible with UNHCR’s data import. | All fields to which the user’s role has access. |
| Custom | Excel file containing all the fields specified by the user. Can be imported back into Primero. | All fields specified by the user, to which the user’s role has access. |

![](img/image57.png)

Once you’ve selected your format, the export window will appear, allowing you to set your own password for the file, and create your own file name.

![](img/image52.png)

To export a list of cases, while in the case list view, you can select as many as you’d like to export via the check boxes:

![](img/image60.png)

To export all cases, you can leave all unchecked and it will export all cases you have access to. The bulk export will generate in the background. You can continue to use the app while it is generating. To access it, click on the tab with the download icon. 

![](/img/image80.png)

To export a single case, you can either check only that case in the case list, or enter into the case to view it, then use the ACTIONS button to export.

# Navigating Primero Forms

Once you are creating or editing a record, you will see a navigation list in the left panel. This list is an organized way to navigate through your forms. The initial titles you see are called **Form Groups** and are set up by your site administrator. The current form you are on will be highlighted - see below:

![](img/case-view-form-group.png)

If a Form Group has only one form, you can simply click on it and it will populate the form. If it has more than one, you can click on the Form Group name or the expand icon to the right of the name to expand it and see all the forms in the group. Once expanded you can then click on any of the form names to enter into the chosen form. For example, in the image above, the user has selected the **Identification / Registration** form group and the **Basic Identity** form.

## Navigating Sub-Forms

In certain data sets and forms, we find that information pertaining to an event or entity is nearly identical. For example, information on specific family members can be the same form, just labeled per family member name and relationship. So in cases like this, we’ve designed these forms as “sub-forms,” and you manually add additional individual forms to add information on family members, individual follow ups, etc. To navigate those, there is an expand/collapse function, and an add/remove function.

## Alerts

When an incident has been added to your case, you will see a small alert badge next to the incident subform. This helps users keep track of updates to a given case's situation and immediately undertake any necessary services.

![](/img/image95.png)

There are two other situations which would cause an alert to appear: the addition of a service provision to your case, and an approval request being made on a case. In the first situation, if another user adds a service provision to your case, an alert will appear next to the Services form tab in the forms side bar. (Depending on your configuration, this form may also be called "Response Overview.")

![](/img/image103.png)

You may also see a message at the top of the form informing you of the reason for the alert.

![](/img/image104.png)

An alert may also appear on a case form if a request was recently requested for case plan, closure, or best-interest assessment approval. Whenever an approval is requested for one of these situations, an alert will appear next to the appropriate form tab: Services (also called Response Overview in some implementations) for case plan approval, Closure for closure approval, and BIA for best interest assessment approval.

![](/img/image105.png)

# Creating, Updating, or Editing a Case

## Creating a Case

To create a case from the case list view, click on the "NEW CASE" button. You will see a modal like the one pictured below. Here, you have two options. The first option is to simply create a case by clicking the "CREATE CASE" button. However, you can also check to see if a case already exists for a child by running a search. \(For a list of fields that are searchable, read the "Quick Search" section.\) To run a search, simply type your search query into the search box and click the "SEARCH" button. This will take you to a search results page. If no search results appear, you can just create a case by clicking on the "NEW CASE" button again on the search screen.

![](/img/image92.png)

Once you have reached the new case page, you can navigate to different forms as we describe in the “Navigating Primero Forms” section.

## Editing a Case

To edit a case, simply located it in the case list view and then click on it. Once you’ve entered into the case you would like to update, you must click the **EDIT** button in the actions header. The page will then refresh and allow you edit individual form fields.

There are a number of different field types in which you can edit differently.

* **Text** - Type normally using your keypad or keyboard.

* **Text Area** - Similar to the Text field. Type normally, the field expands for more information as you continue to enter information.

* **Date** - Multiple ways to edit

  * You can type in a numerical date in the format of dd-mm-yyyy

  * You can type in the first three letters of the month in the format of 01-Jan-2014

  * You can use the calendar widget to go to the correct day and select it directly

* **Check Boxes** - You may click one or many of the options using the mouse.

* **Tick Box** - You may click on the box using the mouse.

* **Select Drop Down** - Click any option to select it.**Multi-Select Drop Down** - Begin typing and either hit ‘enter’ or click to select multiple options.

* **Radio Button** - Similar to Tick Box, click on the correct answer using the mouse

* **Numeric Field** - Key the number into the field.

* **Tally Field** - Key in the number you need for each tally. The total automatically calculates based on the tally fields and is not editable in itself.

When you attempt to save, there is always the possibility that one or more of the fields you entered will be formatted incorrectly. For instance, if you try to fill in the “Date of Registration or Interview” field--which is supposed to be a current or past date--with a date in the future, Primero will be unable to save the information. In this case, after you hit the “save” button, the case will fail to update with your new information, and the “Date of Birth” field’s label will be highlighted in red, to inform you that the field has been entered incorrectly.

![](/img/image102.png)

In addition, it may be possible that, when you try to save, you will have forgotten to fill out some fields that are required. In this case, the required fields will be highlighted in red to inform you that they are required. In addition, a message will appear at the top of the form, telling you which un-filled fields are required, and on which forms these fields are located. In the form tabs, small red numbers will appear next to each form section or form group name to tell you how many fields on each need amending, due to their being either blank or improperly formatted. Another way to tell which fields are required is that each will have a small, red star to its right.

![](/img/image103.png)

![](/img/image104.png)

When a required field is located on a nested subform, a user must either fill out the required field or remove the subform entry with the un-filled field. The red number next to the name of each form section representing the number of un-filled fields in a form section will reflect the total number of required fields across all subform instances in that form section. So, for instance, if there are two required fields on the Family Details subform, and the user has created subform entries for each of three family members without filling out any of the required fields, the number '6' will appear next to **Family Details** form section name in the forms list (2 × 3 = 6).

![](/img/image105.png)

Once again, if you wanted to avoid filling out the fields on one of these subform entries, you could just click the "Remove" button to remove that subform entry. For more information on how you can set which fields are required, please see the **Primero Administration and Configuration Guide**.

# Assignments, Transfers, and Referrals

There are three actions which allow you give another user access to your case: *Assign*, *Transfer*, and *Refer*.

![](/img/assign-transfer-referral.png)

## Assignments

Managers have ability to assign a case to a different user. If you select the Assign option from the Actions dropdown menu, a modal will appear that allows you to select from existing users. Assigning the case will change the record owner to the selected user, that record will no longer be available to the previous case worker.

![](/img/image77.png)

## Transfers

Much like assignments, transfers send a record to a different user. Unlike assignments, however, transfers give the recipient the opportunity to accept or reject the record. If they reject it, the record will stay with its original owner. If they accept it, the recipient will now have full ownership of the record, and the original owner will no longer have access. 

The following modal form will appear and allow you to select options for your transfer. Consent of the individual \(or a consent override\) is required for transfers. You will also be asked if you are transferring to a remote system. This means that you are transferring the case to someone who does not use your Primero system. See the **Transferring to a Remote System** section below for details.

To select the user that you are transferring to, first select the agency and location associated with the user.

![](img/transfer-modal-location-select.png)

Once you have selected an agency and location for your transfer, the "Existing User" field will only display users who are part of that agency and based in that location.

![](img/transfer-modal-filtered-users.png)

If the desired user is not in the drop down, it means this user does not have privileges to be transferred to or that the user does not meet the criteria selected in the Agency or Location fields.

### Transferring to a Remote System

The "Remote System" option allows you to create a password-protected export file which you can give to the recipient.

![](/img/transfer-external-checkbox.png)

The "Type of Transfer" field indicates the level of information access your export file will include. The options in this list will generally be roles in the system which are permitted to see specific forms on the child's case, depending on the role's expertise. For instance, one option might be "Medical Service Provider." Selecting this option will produce an export file which only contains the information a Medical Service Provider would be able to see in Primero.

There are three types of exports which you can create as part of an "external" transfer, each for a different type of recipient:
 * **Primero**: Someone who uses a different instance of Primero. This produces a JSON file which can then be imported into the recipient's Primero instance. 
 * **Non-Primero**: Someone who is using a different type of information management system. This also produces a JSON file.
 * **PDF**: Someone who is not using an information management system, and does not have a user account in Primero. 

![](img/transfer-external-modal.png)

> _Note:  
> When transferring any such password-protected export/import file, the means of sending the file, filename, and the password that opens it, will be determined by the Information Sharing Protocol \(ISP\) decided by the appropriate local steering committee. When determining this policy, on-the-ground security considerations will be at play, as well as the ease and speed of physical transport within the country._

### Accepting or Rejecting Transfers

Based on your deployment's configuration, you may have the ability to accept or reject a case that has been transferred to you. You will be able to see if any cases have been transferred to on your dashboard. If you click on the Referrals and Transfers form for the case that has been transferred to you, you will see that the status is in progress and that there are buttons to either accept or reject the transfer. If you click to accept the case, the status will change to accepted, and you will become the record owner, rather than an “other assigned user”. The record information is updated with this change. If you click Reject, it brings up a dialog box with an OK button and a textbox to enter the Rejection Reason. When you click OK, the rejection reason is saved to the nested subform. The status is changed to 'rejected, and you are removed from 'other assigned users' and no longer have access to the record.

![](img/transfer-recipient-accept-reject.png)

### Requesting a Record Transfer

If you find a record owned by another user and need full access to it, you can ask the record owner to transfer the record to you. In Primero, this is known as a *Transfer Request*. Your ability to perform a *Transfer Request* will depend on your instance's configuration. To request a transfer, first search for your case from the case list view. When you identify the entry in the list for the case you are seeking, click the "View" link at the right of the case's row.

![](/img/image88.png)

Scroll to the bottom of the *View Details* modal. Here, you will see a button marked "Request Transfer". Click it, and a modal will appear.

![](/img/v1-6/image7.png)

![](/img/v1-6/image8.png)

Here, you will see information on the record owner and a text box where you can enter a note to the owner of the record. Click "Send Request" to submit.

#### Notifications for the Case Owner

Once you have sent the transfer request, the record owner - if their user account is configured with an email address and the ability to receive email notifications - will receive a notification telling them about your request for a record transfer.

![](/img/v1-6/image9.png)

If the case owner clicks on the link in the email, they will be redirected to the Primero login page and then to the case record, where they will see a notification in the forms side bar and on the *Transfers and Referrals* form alerting them to the transfer request. Here, they will also see the note you included in your request.

![](/img/v1-6/image10.png)

![](/img/v1-6/image11.png)

At this point, the record owner can choose whether or not to transfer the record to you.

## Referrals

Referring a record is a way of giving a user limited access to a record without transferring it completely. While referring a record allows the recipient to access your record, the referring user will maintain full record ownership and will be able to remove the recipient's access at any time. To refer a record from either the individual record page or the list view, go to the Action menu at the top of the page and select "Refer Case."

You may also refer a case directly from the services subform. For more information on how to do this, see the **Referring From Services Form** section below.

The following modal form will appear and allow you to select options for your referral.

![](/img/referral-modal.png)

As with transfers, consent of the individual is required for referral. Consent for referral is found on the Data Confidentialty form under the Identification/Registration Form Group. 

The following fields are important for selecting a user:
 * **Service** you are requesting the other user perform
 * **Agency** you would like to perform the service
 * **Location** where you would like the service to take place

![](/img/referral-modal-narrow-down-users.png)

Now, select the “Existing User”--a user within your deployment of Primero. A list of all users that perform the service selected, from the agency selected, and in the location selected will appear. If the desired user is not in the drop down, it means this user does not have privileges to be referred to or does not meet one of the three criteria listed above.

For more information on how to specify the Agency a user belongs to, the Location where they are based, and the Services they offer, please see the **Primero Administration and Configuration Guide**.

### Referring to a Remote System

The "Remote System" option allows you to create a password-protected export file which you can give to the recipient.

![](/img/refer-external-checkbox.png)

The "Type of Referral" field indicates the level of information access your export file will include. The options in this list will generally be roles in the system which are permitted to see specific forms on the child's case, depending on the role's expertise. For instance, one option might be "Medical Service Provider." Selecting this option will produce an export file which only contains the information a Medical Service Provider would be able to see in Primero.

There are three types of exports which you can create as part of an "external" referral, each for a different type of recipient:
 * **Primero**: Someone who uses a different instance of Primero. This produces a JSON file which can then be imported into the recipient's Primero instance. 
 * **Non-Primero**: Someone who is using a different type of information management system. This also produces a JSON file.
 * **PDF**: Someone who is not using an information management system, and does not have a user account in Primero. 

![](img/refer-external-modal.png)

> _Note:  
> When referring any such password-protected export/import file, the means of sending the file, filename, and the password that opens it, will be determined by the Information Sharing Protocol \(ISP\) decided by the appropriate local steering committee. When determining this policy, on-the-ground security considerations will be at play, as well as the ease and speed of physical transport within the country._

### Revoking a Referral

To remove a referral recipient's access to a case, start by editing the case using the **EDIT** button.

![](/img/case-edit-button.png)

In the **Record Information** form, find the _Other Assigned Users_ field. Under this field, there will be a link labelled "Remove Referrals." Click this.

![](/img/referral-revoke-1.png)

The field will now allow you to remove the names of users who have access to the case. Click the 'x' next to the name of the user whose access you would like to revoke.

![](/img/referral-revoke-2.png)
![](/img/referral-revoke-3.png)

Once you have removed their name from the list, click **SAVE**. The referral recipient will no longer have access to the case.

![](/img/case-save-button.png)

For more information about how to edit a case, please see the **Editing a Case** section.

### Relinquishing a Referral

Based on the deployment, you may have the ability to relinquish a case that has been referred to you. You can see if any cases have been referred to you on your dashboard. When you click on the **Referrals and Transfers** form for the case that has been referred to you, you will see a DONE button next to the referral that has been made to you. If you are done reviewing the case, you can click the done button. Once clicked, it will be removed from your case list and you will no longer have access to it.

![](img/image82.png)

# Services

A core part of the case management process is responding to the needs of a case. Primero manages these through the **Services** form and through the provision of services (sometimes also referred to as "responses").


## Services Form

To add a service to a case, simply go into the **Services** form on the case edit page, and click the "add" button. You will see a subform like the one in the picture below. Here, you can enter information on the service.

![](img/image96.png)

When selecting a "Type of Response", remember that this will help determine the workflow status of your case. So, for instance, if you select "Action Plan," your workflow status will also be "Action Plan" so long as you do not add any other services or close the case.

![](img/image97.png)

Another important field to fill in is the type of service that will be rendered for this particular response, whether it be medical, legal, or whatever other options have been specified in your implementation's configuration. This field will help service providers properly take care of your case.

![](img/services-subform-select-service-type.png)

Choosing a timeframe for the service will help generate reminders in you or your manager's dashboard when the service is coming due or overdue. This timeframe, depending on your configuration, will take one of two forms: the time period after which the service will be due (e.g. three hours, one day); or the actual due date for the service (e.g. November 30, 2017). Both these forms are displayed in the pictures below. For more information on these reminders, check out the Dashboards section.

![](img/image101.png)

![](img/image106.png)

Selecting a service provider in this form will allow you to refer your case to the service provider directly from the form. When selecting a service provider, fill in Implementing Agency and Service delivery location. When you fill in the "Service Provider Name" field you will be shown a list of users filtered by the selected agency, delivery location, and service type. So, for instance, if you specified the "ACTED," "Psychosocial Service," and "Dahuk", you will only see users which are part of ACTED, located within Dahuk, and capable of providing a Psychosocial Service.

![](img/services-subform-filter-users.png)

## Referring from **Services** Form

Once you have saved the case with this new service, and have been redirected back to the view page, go to the **Services** form and the service you just added. If you have filled out the the _Response Type_, _Service Type_ and _Service Provider Name_ fields for your service, the "REFER" button will appear in the subform header.

![](img/services-subform-refer-button.png)

Click on this button, and you will see a modal like the one pictured below. Here, you can enter information on your referral just like you normally would. However, if you have already filled out a service provider and a service type for your service, these fields will be pre-entered for you. Remember to ensure that your case has provided consent, or that you choose the override consent option before referring.

![](img/services-subform-referral-modal.png)

# Workflow Status

## The Workflow Status Bar

The **Workflow Status** allows the user to quickly understand where in the case management process the current case stands. This value can be seen at the top of the case forms, in the **Workflow Status Bar**. By default, Primero is not set to display this bar, but the system can be configured to change this. (See the **Primero Administration and Configuration Guide**.)

![](img/image107.png)

Above is the default **Workflow Status Bar**. Here you see the following statuses: "New," "Case Plan," "Care plan," "Action plan," "Service provision," "Service Implemented," and "Closed." The first of these statuses, "New," is applied when a case is first created. The second, "Case Plan," is applied after the "New" status, when the field "Date Case Plan Initiated" (or any other field with the id "date_case_plan") is filled out by the user.

The next three statuses, "Care plan," "Action plan," and "Service provision," correspond to the three potential "Response Type" values for a service. A case is given one of these statuses if the case is still open, and still has non-implemented services planned for it. The "Response Type" value for the most-recently-added, non-implemented entry in the **Services** form will be the new workflow status.

![](img/image108.png)

For example, let's suppose I have a case with three services: one created on June 1 with a type of 'Action plan' which is *implemented*; one created on June 20 with a type of 'Care plan' which is *not implemented*; and one created on June 25 with a type of 'Service provision' which is *implemented*. In this situation, the case's workflow status would be 'Care plan', since this is the Response Type of the most-recently-added, non-implemented entry in the **Services** form.

These statuses will vary depending on the options in your configuration for the "Response Type" lookup. So, for instance, if your "Response Type" options are "Remote Contact" and "In-Person," you will see these two as potential workflow statuses, rather than the three that we see here.

The next status, "Service provision," is deprecated, and should be left out of any configuration. The "Service Implemented" status, meanwhile, applies when all of the entries in the **Services** form have been implemented. One of these services is considered implemented if the "Service Implemented" field (or any field with the id "service_implemented") on the service subform is set to "Implemented."

Finally, the "Closed" status applies when a case's case status has been set to "Closed."

Please see the **Primero Administration and Configuration Guide** for more details on how to change which workflow statuses appear for your implementation.


# Notification Emails

Users may receive notification emails that either welcome them to the application, or alert them to changes to their cases. Only user accounts which have been designated to receive notification emails will receive anything, and only if the system as a whole has been set to send notification and welcome emails. The following users will receive emails in the following circumstances:

* Managers whose case workers have requested approval for case plans, closures, etc.

* Case workers whose managers have responded to approval requests for case plans, closures, etc.

* Users who have received a case transfer

* Users who have received a case assignment

* Users who have received a case referral

Welcome emails will look something like the below message. If the new user clicks the "Primero" link in the message, they will be sent to the system login screen. Once again, users will only receive welcome emails if the system has been configured to send them, and if the user in question has been set up to receive them.

![](img/image117.png)

For more information on how turn welcome and notification emails on or off in the system's configuration, please see the **Primero Administration and Configuration Guide**.

# Tracing

Using Primero's **Tracing** functionality, users can perform searches on behalf of parents or guardians looking for unaccompanied or separated children.

## Consent for Tracing

**IMPORTANT NOTE**: Cases will only appear as potential matches for tracing request if they have provided consent for tracing. Users can record a case's consent to take part in tracing by filling out the tracing consent field in the "Data Confidentiality" form. This field is pictured below.

![](/img/v1-6/image13.png)

## Tracing Requests

If your user is configured for tracing activities, you should have access to **Tracing Requests**, and you should see the "Tracing Requests" link in the navigation bar at all times.

![](/img/v1-6/image14.png)

If you click on this link, you will see a list of all the tracing requests you have access to. Click "New Tracing Request" to begin tracing.

![](/img/v1-6/image15.png)

First, you will fill out the "Inquirer" form. This contains information on the parent or guardian who has initiated tracing. Primero will use much of the information in this form to search against information recorded about family members in each case's "Family Details" subform entries. So, for instance, if a child's father, named "Ibrahim," is the inquirer, Primero will search for cases with a family member whose relationship to the child is recorded as "Father", and whose name is "Ibrahim."

![](/img/v1-6/image16.png)

Next, you will fill out information on the child by filling out a subform entry in the "Tracing Request" form. Primero will use the information here to search for cases with similar attributes. So, for instance, if the father mentioned above is looking for a daughter named "Fatima," who is 15 years old, Primero will search for cases with the name "Fatima" and an age of 15.

![](/img/v1-6/image17.png)

## Matches

Once you have saved the tracing request, you will see a "Find Match" link at the top of your "Tracing Request" subform.

![](/img/v1-6/image18.png)

If you click on this link, you arrive at a page which displays a number of cases which are potential matches for your tracing request. This list will contain the case's ID, the record owner's user name, the record owner's agency, the approximate likelihood of the case being the right match (either "Possible" or "Likely"), and (depending on your user's configured permissions) a link which displays the *View Details* modal (See "Viewing Record Details" section above).

![](/img/tracing-from-tr-match-list.png)

The records provided as potential matches are based a scoring system that weight many attributes as detailed in the scoring section below. 

### Scoring

Primero gives potential matches a score based on how similar they are to the tracing request *compared to other potential matches Primero has found*. This means that, if scoring were done on a 1-10 scale, the lowest potential match in a list would get a score of 1, the highest would get a 10, and the median match would get a 5. A high scoring match Primero will record as "Likely" and a medium-to-low scoring match, Primero will record as "Possible."

When looking at the potential matches for your tracing request, you can see which case attributes matched your tracing request by clicking on the score label (Likely or Possible). This will reveal a modal which compares a number of case attributes side-by-side with the attributes you gave your tracing request. Attributes which are the same get a '✔', attributes which are different get a red 'X', and attributes which were left blank on both the case and the tracing request get a '-'. 

![](/img/tracing-score.png)

### Adjustable Matching Criteria

On the right side of the screen you will see a dynamic list of fields named "Matchable Case Fields." Each form containing matchable fields is represented by a select box representing a Case or Tracing Request form. For instance, the _Basic Identity_ field contains all attributes used for matching found on the **Basic Identity** form.

![](/img/matching-criteria.png)

By selecting the dark grey 'X' on each attribute you can remove any attribute that you do not wish to use for comparing cases and tracing requests in the current matching search. If you wish to add an atribute to the the searching criteria, simply begin to type the attribute into select box of the form the attribute is found on. Only fields which are included in the global Matching Configuration will be available. (For more information on which fields are included in the global Matching Configuration, contact your Primero Administrator.) After modifying the matching criteria, click **APPLY**.

![](/img/matching-criteria-selection.png)

The matching results will change based on your new criteria. To see more details about a potential match, click the "View" link to the right of the result (this may or may not appear, depending on your configuration).

![](/img/tracing-from-tr-match-list-view-link.png)

You will then see the *View Details* modal, which will display a number of attributes of the case. (For more information on the *View Details* modal, please see the **Viewing Record Details**) section above.

### Linking Tracing Requests with Cases

Once you have identified a match which you think is the correct one, you can link this case to your tracing request, provided your user is configured to be able to see the case record in its entirety. If so, you should be able to click on the case's ID.

![](/img/tracing-from-tr-match-list-select-case.png)

You will now arrive at the case record page. At the top of the page, you should see a button that says "Match." 

![](/img/tracing-from-tr-case-match-button.png)

Click on this button to link the case to your tracing request. You should then see a notification at the top of the screen, indicating that your match succeeded.

![](/img/tracing-from-tr-case-match-notification.png)

Now, if you return to your tracing request's list of matches by hitting the back button, you will see that the entry for the case you just linked to your tracing request is in bold.

![](/img/tracing-from-tr-match-list-matched.png)

Similarly, when the user responsible for the case goes to the case's "Tracing and Separation Details" form, they will see a label marked "Matched tracing request," and to the right of this, a link to the tracing request which you created.

![](/img/tracing-from-tr-case-matched-tr-link.png)

At this stage in the tracing process, the user who initiated the tracing request would manually contact the user and/or agency responsible for the case to initiate the verification and reunification process.

### Initiating Tracing From a Case

Depending on the system's configuration, some users may also be able to search for matching tracing requests from the View Case page. A case must have indicated consent for tracing in order for a user to have access to this feature. This field will be found on the **Consent** / **Data Confidentiality** form.

![](/img/tracing-from-case-consent.png)

Once you indicate that the child has given consent to share information for tracing and save the case, you should see a button marked **FIND TRACING MATCH** at the top of the View Case page.

![](/img/tracing-from-case-button.png)

If you click on this button, you will arrive at a list of potentially matching tracing requests for your case.

![](/img/tracing-from-case-match-list.png)

# Reports

Reports allow users to see a high-level, aggregate view of data, helping them to understand trends and coming challenges in their work. Only certain roles--and thus certain users--will have the ability to create or view reports. Some users will be able to navigate to the **Reports** section of the application and view existing reports but not edit them or create new ones, while others will have the ability to view, create, edit, and export reports.

## Creating a Report

To create a report, first click the **Reports** icon in the top toolbar. You will see that there are already a number of pre-built reports which you can view at any time. To start your own, click the **Create Report** button at the top of the screen.

![](img/image23.png)

When you have reached the new report form, be sure to enter a name and description for your report. You must then specify the module from which to draw the records for your report, as well as the type of records you want to be drawing upon. Here, we have chosen the Child Protection module, and the Case record type.

![](img/image54.png)

Next comes choosing the row and column attributes by which you want your data to be grouped. The first item you choose in each field will be the outer grouping layer, with each successive item acting as a sub-categorization. Taking a look at the example below, we can see that the columns of our report have been first divided by sex, and then sub-divided by permanent district/chiefdom, since these are the first and second “Group by column” attributes, respectively. We can see that the rows of the report follow the same pattern.

![](img/image59.png)

![](img/arrow-down.png)

![](img/image51.png)

The columns of your report will be augmented by a final “Total” column, which shows the aggregate for each row. It is important to note that the numbers in each of your columns may not add up to the number in your total column, since many attributes will go undefined by the workers doing registration. For instance, in the example below, three cases with the “child has been abandoned” protection concern were never assigned a sex, resulting in a report with one female, no males, and four total cases.

![](img/image24.png)

Furthermore, any reports based on fields within certain nested forms will automatically count a field for each saved record, even if a nested form for this field was never filled out. This is because Primero automatically populates an empty subform on the page for form sections such as “Protection Concerns,” so that the user can easily enter information. When a user fails to enter information for that field, however, the field still counts as a single item. For instance, if you were to create a case and fail to enter any information into the blank Protection Concerns subform, a report outlining how many cases had each type of protection concern would still count your case as having a single protection concern type, even though you had never entered any information on the Protection Concerns subform. This would then count into the total, without counting into the column for any single one of the protection concern types. Taking a look at the example below, we can see that, in the Freetown district, one child has been registered as abandoned and one with a protection concern type of “Extreme levels of poverty.” But the total number of protection concerns for this district is three, meaning that one case was registered with a protection concern form where the protection concern type was never filled in.

![](img/image61.png)

After you have defined the row and column attributes for your report, you will choose the fields from which you will receive an aggregate count. This feature obviously only works on numeric fields. To give an example of how it works, imagine we have a report that disaggregates your cases based on number of children in the family and date of birth \(by year\). Three cases end up going into the report: one born in 2004 whose family has three children, one born in 2001 whose family has six children, and another born in 2001 whose family also has six children. Here is what the report would normally look like:

![](img/image49.png)

As you can see, the 2001 column has the number “2” in the “7” row, since there are two cases born in 2001 whose families have seven children. We see this same number in the “Total” column for the “7” row for the same reasons. If we choose to have aggregate counts on the “Number of children” field, however, the report would look like this:

![](img/image06.png)

Now, instead of seeing that there are two cases that meet the criteria for being born in 2001 and having a family with seven children, we instead see the number “14,” representative of fourteen total children. Once again, this field also shows up in the “Total” column.

### Age Range

The next field, specifying age range, helps make reports involving age more manageable by grouping them into a smaller list of ranges. The two images below exemplify the usefulness of this feature. The first shows part of a sprawling report without age ranges enabled. The second shows the same report with age ranges.

![](img/image62.png)

![](img/arrow-down.png)

![](img/image66.png)

### Date Ranges

The next field, “Use date ranges,” allows you to do much the same thing, but with date fields instead of ages. Now, instead of having to have a column for every date over a two year period--as would be the case with the default, day-long range--you can disaggregate your records by whether or not they fit into week-, month-, or year-long spans of time.

### Filters

Next, you can put filters on the records you are using to eliminate irrelevant data. By default, each report filters to include only those records with a “Case Status” of “Open” and a “Valid Record?” value of “Yes.” You can create a filter on any single-select, multi-select, tick box, check box, radio button, number, tally, or date field, and for each one, you can specify which values are acceptable for records being included into the report.

Finally, you are asked whether you would like to generate an exportable graph of your report.

## Viewing your reports

If you click save on your report, and it saves successfully, you should arrive at the view page for your report. You will first see a table representing your report. Above the table, you should see either one or two tabs. The first, marked “Table,” represents what you currently see. The second, which will only appear if you specified that your report should generate a graph, will be marked “Graph” and will show you just that.

![](img/image70.png)

You can also use the **Export** button above the tabs to export either the data \(in CSV form\) or the graph \(as a .png image file\). Below is an example of a graph generated and then exported from a report.

![](img/image47.png)

