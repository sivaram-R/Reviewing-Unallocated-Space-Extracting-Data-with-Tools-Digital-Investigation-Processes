# Reviewing-Unallocated-Space-Extracting-Data-with-Tools-Digital-Investigation-Processes
### Reg no:212222100050
### Name: Sivaram R
## AIM:
To review unallocated space in a disk image, extract data using forensic tools, and understand the digital investigation process.

## DESIGN STEPS:
### Step 1:
Use tools like Autopsy or Sleuth Kit (blkls, icat) to identify and analyze unallocated space.

### Step 2:
Extract data from unallocated space and examine for hidden or deleted content.

### Step 3:
Document and interpret findings as part of the digital investigation process.

## PROGRAM:
Data Extraction and Investigation Tool Usage

```
lsblk
```
````
sudo dd if=/dev/sda of=/home/kali/disk.img bs=512
````
```
mmls ~/disk.img
```
```
sudo ls -lh disk.img
```
```
strings disk.img | less
```


## OUTPUT:
![image](https://github.com/user-attachments/assets/28a1ec86-1e18-4043-ae1f-82a1493d1a70)

![image](https://github.com/user-attachments/assets/d53af4b0-1ead-4fee-b0b6-b6355ac8f946)

![image](https://github.com/user-attachments/assets/c5ca0ddd-1bf6-4227-bcef-d2334ee61e7f)

![image](https://github.com/user-attachments/assets/09629f7c-88c7-464a-8ed2-145bf6345d6e)

![image](https://github.com/user-attachments/assets/6de06d3b-837c-44e6-94a0-8e3c3ecc618a)


## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.

