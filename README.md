# Bahmni Implementation
# Bahmni consists of Electronic Medical Record Management System (EMR), Enterprise Resource Planning (ERP) and Laboratory Management System (LMS).
# All these components are based on Open Source. EMR is based on OpenMRS, ERP is based on OpenERP and LMS is based on OpenELIS.
# Bahmni is User Interface layer on top of OpenMRS.


# Start
Following are the _table.scss file contents for generating CSS of clinical.css 
/*scroll in investigation chart table*/
table.investigation-chart {
	max-height: 250px;
	overflow: auto;
	display: block;
	border: 1px solid #ddd;
	tr {
		border: 1px solid #ddd;
		td {
			border-left: 1px solid #ddd;
		}
	}
	thead {
		th {
			position: sticky;
			top: 0px;
			z-index: 10;
			border-left: 1px solid #ddd;
		}
	}
	tbody {
		th {
			position: sticky;
			top: 0px;
			border-left: 1px solid #ddd;
		}
	}
}
# End
