# AttachmentManager

The **AttachmentManager** QGIS plugin enables users to store, view, and delete documents (files) linked to geographic features in a PostGIS database.

## Use Cases

For example, you can use AttachmentManager to:

- Store construction drawings directly on the individual pipes in a utility network  
- Save images of installed key cabinets on specific building polygons  
- Attach spreadsheets containing analysis data to specific points within an area of interest  

## Functionality

When the plugin is activated, it will:

1. Check whether the active layer is a PostGIS layer  
2. Check whether an associated attachment table already exists  

### If an attachment table exists:
- A list of attachments for the selected feature is displayed  
- Users can:
  - Open/show attachments  
  - Delete attachments  
  - Add new attachments  

### If no attachment table exists:
- A new attachment table can be created with a single click  

## Key Features

- Supports PostGIS layers  
- Simple attachment management interface  
- On-demand creation of attachment tables  
- Unlimited number of attachments per feature  

## Notes

- There is no limit to the number of attachments that can be associated with a single feature  
``
