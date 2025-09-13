# Using-the-Autopsy-retrieve-the-deleted-files

## AIM:
To use Autopsy in Kali Linux to retrieve and analyze deleted files from a disk image.

## DESIGN STEPS:
### Step 1:
Open Autopsy and create a new case with appropriate case details.

### Step 2:
Add a disk image as a data source and let Autopsy analyze the content.

### Step 3:
Navigate to the "Deleted Files" section in Autopsy and examine or recover the deleted files.

## PROGRAM:
### **1. Copy Files to the Virtual Disk**  
- Open **File Explorer** → Go to the new drive (`C: or D:`), where the folder created in the New Virtual Disk
- Create a new folder (`Autospy`) and copy **images or files** into it.  

### **2. Delete the Files**  
- Select any one or two images → Press **Delete**.  
- Empty the **Recycle Bin** to permanently delete them.  

### **3. Recover Deleted Files Using Autopsy**  
### **Open Autopsy & Create a New Case** 

- Launch **Autopsy** and **Run as a administrator**  
- Click **Create New Case**.  

![Screenshot 2025-05-22 182722](https://github.com/user-attachments/assets/470376e5-91da-422f-91bc-d09ad7e7042e)
- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  
![Screenshot 2025-05-22 182808](https://github.com/user-attachments/assets/4f6c0230-ab98-407b-b03d-235b9b8f1ccc)



### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**

- Select **Local Disk** → **next**

- Select Disk → **Choose the VHD drive (`Drive1`)**

- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).
- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  
![image](https://github.com/user-attachments/assets/5a1f61d6-eab6-4d36-a2f1-315cad40f6b8)

- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.
![image](https://github.com/user-attachments/assets/b3dd9324-2662-4ab6-ba34-16e55aff7511)



## OUTPUT:
## Folder before deleting the files
![Screenshot 2025-05-22 183838](https://github.com/user-attachments/assets/5bfa9258-b83e-4cd5-bad3-0d16bd4ceb72)
## Folder after deleting the files
![Screenshot 2025-05-22 183813](https://github.com/user-attachments/assets/bdba200d-9c9e-4a5c-8b6a-e39d1f7aa0ec)
## Foldet after extracting the deleted images using autopsy
![image](https://github.com/user-attachments/assets/aa880e70-f179-46f7-b26d-14d2a318c412)


## RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
