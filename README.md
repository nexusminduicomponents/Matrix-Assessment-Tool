
# Matrix Assessment Tool

The Matrix Assessment Tool is a robust and flexible solution designed for Model Driven Apps and Microsoft Dataverse. This tool enables businesses and organizations to effectively assess, analyze, and manage complex data sets and processes through customizable assessment matrices. The Matrix Assessment Tool leverages the power of the Microsoft Power Platform to provide a seamless, user-friendly experience for data-driven decision-making.


## Features
### Comprehensive Data Integration

Integrates seamlessly with Microsoft Dataverse, utilizing existing data structures and relationships for real-time data synchronization.

### Customizable Assessment Matrices

Create and configure custom assessment matrices tailored to specific business needs.

Supports various matrix types such as performance evaluations and risk assessments.

### User-Friendly Interface
Model-driven app interface designed for ease of use and accessibility.

### Scalability and Flexibility
Designed to scale with organizational growth and evolving needs.

Adaptable to various industries and assessment criteria.

## Benefits
### Improved Decision-Making

Data-driven insights for informed decision-making and strategic planning.

### Efficiency Gains
Automation of time-consuming assessment processes, reducing manual effort and increasing efficiency.

### Enhanced Accuracy
Consistent and accurate assessments through standardized evaluation criteria and processes.

### Risk Mitigation
Identification of potential risks and areas for improvement to mitigate issues before they escalate.

### Regulatory Compliance
Maintains compliance with industry standards and regulations through systematic assessments.

## Getting Started
### Prerequisites
Access to Microsoft Dataverse

Microsoft Power Platform (Power Apps, Power Automate)

Appropriate permissions for creating and managing Model Driven Apps

### Installation
Installing the Matrix Assessment Component Packages.

1) Download _ColorPicker managed solution and import in your dataverse.

2) Download _EntitySelector managed solution and import in your dataverse.

3) Download _Slider managed solution and import in your dataverse.

4) Download _MatrixAssessment managed solution and import in your dataverse.

5) Download MatrixAssessment_App managed solution and import in your dataverse.







## Screenshots

![App Screenshot](https://res.cloudinary.com/pakgarage/image/upload/v1718810209/image_ddqanp.png)

![App Screenshot](https://res.cloudinary.com/pakgarage/image/upload/v1719052325/Screenshot_2024-06-22_153117_wliogp.png)


## Model Driven App

### Integrate in Model Driven App

After importing solutions go to your https://make.powerapps.com/ 

Under App section 

Run the Matrix Assessment Tool Model Driven App

![App Screenshot](https://res.cloudinary.com/pakgarage/image/upload/v1718900353/Screenshot_2024-06-20_211759_oluuet.png)

First Screen will appear is Matrix Configuration.

In this section you can add configuration of your Matrix and also you can customize the layout of the Matrix.
 ![App Screenshot](https://res.cloudinary.com/pakgarage/image/upload/v1718900467/Screenshot_2024-06-20_212050_wahh95.png)


## Configuration Settings

 ![App Screenshot](https://res.cloudinary.com/pakgarage/image/upload/v1720954177/Screenshot_2024-07-14_153520_cckpok.png)
#### This section describes the settings in the configuration interface for the "Account" entity.

### Fields

#### Name (required)

#### Description: 

The name of the configuration setting. For this example, the name is set to "Account".

#### Input Type: Text field
Notes: This field is required and cannot be left blank.

#### Target Entity (required)

#### Description:

The entity to which the configuration setting applies. In this case, it is also set to "Account".


#### Input Type: Dropdown menu
#### Notes: 
This field is required and must be selected from the available options.

#### Font Size (Available in next version)

#### Description: 

The font size for the text in the configuration setting.

#### Input Type: Text field

#### Notes: 

This field is optional. If not specified, a default font size will be used.

#### Font Weight (Available in next version)

#### Description: 

The weight of the font for the text in the configuration setting.

#### Input Type: Text field 

#### Notes: 

This field is optional. If not specified, a default font-weight will be used.

 ![App Screenshot](https://res.cloudinary.com/pakgarage/image/upload/v1720954754/Screenshot_2024-07-14_155158_qa2ddl.png)

## Not Applicable Configuration Settings

#### This section describes the settings available in the configuration interface for the "Not Applicable" section.

#### Fields


#### Risk Level Not Applicable (required)

#### Description:

Specifies that the risk level is not applicable.

#### Input Type: Text field
#### Default Value: "Not Applicable"
#### Notes: 

This field is required and cannot be left blank. You can override the default as per your requirements

#### Not Applicable Background Color (required)

#### Description: 

The background color is to be used when the risk level is not applicable.

#### Input Type: Color picker

#### Default Value: #4096FF, 47%

#### Notes: 

This field is required. The color is specified using a hexadecimal color code and you can specify the color as per your requirement.

#### Impact Rating (Not Applicable) (required)

#### Description: 

The impact rating when the risk level is not applicable.

#### Input Type: Slider

#### Notes: 

This field is required. The slider allows the user to select an impact rating value as out of 100.

## You can repeat the same step for others "Risk Level" as mentioned above.


## Matrix Category Configuration Settings

### This section describes the settings available in the configuration interface.

#### Fields Name (required)

#### Description: 

The name of the matrix category. For this example, the name is set to "Commercial & Contractual".

#### Input Type: Text field
#### Notes: 

This field is required and cannot be left blank.

 ![App Screenshot](https://res.cloudinary.com/pakgarage/image/upload/v1720955005/Screenshot_2024-07-14_160130_xjxgfb.png)

#### Matrix Configuration (required)

#### Description:

The configuration setting is related to the matrix category. In this case, it is linked to an "Account" configuration.


#### Input Type: Lookup field
#### Notes: 

This field is required and must be selected from the available options.

### Actions
#### Save: 

Save the current configuration.

#### Save & Close: 

Save the current configuration and close the interface.

#### New: 

Create a new configuration entry.

### Repeat the same step for others "Matrix Category Configurations"


## Matrix Factors Configuration Settings

 ![App Screenshot](https://res.cloudinary.com/pakgarage/image/upload/v1720956047/Screenshot_2024-07-14_161013_nazry5.png)


#### Description:

The configuration setting is related to the matrix factor. In this case, it is linked to an "Customer" configuration.
Business Requirements Matrix

This matrix is used to categorize the business requirements for a project based on the level of detail and clarity provided by the customer. 

#### The matrix has five categories:

#### Not Applicable: 
The requirements are fully documented by the customer and validated technically.

#### Low: 
#### Description: 

The name of the matrix factor risk level. 

#### Input Type: Text field
Notes: This field is "optional" and can be left blank.

#### Medium: 
 #### Description: 

The name of the matrix factor risk level. 

#### Input Type: Text field
Notes: This field is "optional" and can be left blank.
#### High: 
 #### Description: 

The name of the matrix factor risk level. 

#### Input Type: Text field
Notes: This field is "optional" and can be left blank.

#### Critical: 
 #### Description: 

The name of the matrix factor risk level. 

#### Input Type: Text field
Notes: This field is "optional" and can be left blank.

### Repeat the same step for others "Matrix Factors Configurations"
 


## Contact

For questions, issues, or feature requests, please open an issue in this repository or contact us at nexus.mind.uicomponents@gmail.com.
