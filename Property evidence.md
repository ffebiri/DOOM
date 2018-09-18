# Property Evidence Tool
<p>The tool is use to keep records of properties of the organization(Foxconn) which are been used by individual employees or used by offices within various depatments.

[Link to tool On GlobalNet](https://globalnet.cz.foxconn.com/en-GB/Home/Login "Link to the Tool on Production")
<p/>

![image](C:/Users/ffebiri/Desktop/ui22.png "Location on Global Net")

> Property evidence : This tool accepts entry and shows records of assets(Property) 

 * Accepts Entry of New Recoreds.
 * Enable Edit of Record
    >Tip:You need the correct user right to edit
 * Delete an exixting entry from records
 * Update Exixting Records
 * Import Record in .xls format
 * Upload record Using an Existing Templete.
  
![image](C:/Users/ffebiri/Desktop/1.png "UI of Property Evidence Tool")

```

```
## Evidence Details Tool
> Tip: - **A Helper tool for Property Evidence tool**

### Detail Usage
* Helps to manually load Data into DB which is been used by filters of  property evidence
* You need the correct user right(Admin) to be able to load data into this DB.
   >Tips: Rights needed for Property Evidence tool  
   >> Propert_Evidence 
   >>> Propert_Evidence_edit - Needed for grid edit

   >Tips: Rights needed for Property Evidence Details tool  
   >> Propert_Evidence_Details
   >>> Propert_Evidence_Details_edit - Needed for grid edit
```

```
> Tip: You need to have user right before you can access this option

### Filters and Buttons 
 * Department - Dropdown to help you filter grid according to selected department code
 * Name - Dropdown of all Registerd names.
 * Material - Filter gride according to material selected
 * HW Status -
 * SW Status - 
 * Period - Filter record according to time range.

![image](C:/Users/ffebiri/Desktop/ui.png "Grid Display")

### Grid Columns
* AddNew Button - Used in adding a new record
* Name - Name of the requestor for this item
* Department - Specfic Unit within the organization
* Material - Material taken eg.Notebook, Monitor etc
* HW Status - 
* SW Status - 
* EV Number - Unique number assiged to this property
* From - Initial date item was taken or entered
* To - Final date of receipt of Item
* Comments - Specific comments about entry
* EditBy - Hidden in gridview but automaticalled added saved and vissible in DB
* EditDate - Hidden in gridview but automaticalled added saved and vissible in DB
  
### Grid Editing
<p>
Gride allows In-Line editing. This means when the edit button is click, the user has the oppoertunity to change all entries in the specific row. 
<p/>

### Data Import 
<p>


<p/>

### Data Export 
<p>


<p/>
