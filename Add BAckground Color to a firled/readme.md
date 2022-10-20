Step1:Login to your ServiceNow instance
Step2:Navigate to ALL -> tablename.list {say incident.list}
Step3:Select the field to which you wish to apply your code for Background color change
Step4:Right-click the field label on the form and select 'Configure Styles'
Step5:Style [sys_ui_style] table will open. Provide required input for below fields:
 1. Table [Table that contains the field]: Incident
 2. Field Name [The field to which the style applies.]: Number
 3. Value [The exact value or script-based-condition required to apply the style]: Leave Blank
 4. style [The CSS style to apply]
		 background-color:black;
		 font-size:18px;
		 color:white;
		 
Note: Make sure right application scope is selected or scope is GLobal according to your requirement.
