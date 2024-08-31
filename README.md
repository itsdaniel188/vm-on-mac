Walkthrough guide on how to I installed, configured and updated kali Linux on a virtual machine (MAC M1)

Step 1: ![image](https://github.com/user-attachments/assets/e0d6368b-5f8d-4452-a9dd-c6e2a589a6e4)
Visit UTM store to install UTM on mac, which is equal to installing virtualbox

Step 2: A linux image will be needed which can be installed by visiting https://www.kali.org/get-kali/#kali-installer-images
<img width="468" alt="image" src="https://github.com/user-attachments/assets/048f10a0-13b1-42cc-9272-dda81c5dbcc7">

Step 3: In the UTM interface there are 4 options presented
<img width="468" alt="image" src="https://github.com/user-attachments/assets/0bbc1e07-77e9-4afe-ab94-e745abfdf7a5">
Select create a new virtual machine

Step 4: I selected Linux operating system
<img width="468" alt="image" src="https://github.com/user-attachments/assets/343f98f9-d959-4d11-b3b7-d5eba85b1270">

Step 5: When presented with the image selection screen, I selected browse and attached the linux image that was recently installed in step 2
<img width="468" alt="image" src="https://github.com/user-attachments/assets/af1e9cdf-20ae-4faf-8e8f-84dc1dc935b8">

Step 6: Used default settings and selected continue
<img width="468" alt="image" src="https://github.com/user-attachments/assets/02ac9859-b314-47da-9565-6c3dfd9bd354">
<img width="468" alt="image" src="https://github.com/user-attachments/assets/6b4a882b-5858-42e9-9f36-0f304cd2d2e6">

Step 7: Once finalized, I selected settings icon on the upper right hand corner of UTM window
<img width="468" alt="image" src="https://github.com/user-attachments/assets/3b949372-4c47-4f52-979f-4157a9d2be61">
adjusted settings as seen below
<img width="468" alt="image" src="https://github.com/user-attachments/assets/623f1faf-6f10-4ea1-abb5-609cb0327b43">

Step 8: I was stuck here as when initally attempting to boot up the vm, I would receive errors. Upon further investigation I learned that to set up the vm, a secondary terminal for the vm was created in order for it to boot up successfully.![image](https://github.com/user-attachments/assets/c5ba4049-2a58-4b05-9fba-1f352ad4d274)
Kali linux instance finalized
<img width="454" alt="image" src="https://github.com/user-attachments/assets/5e219422-bd66-4810-86e9-fa29f824d5ab">

Step 9: Used following sudo commands in the images to ensure up to date patches and updates were applied
<img width="468" alt="image" src="https://github.com/user-attachments/assets/75ed8dc8-28ad-4db6-b36d-f7d4961d12c6">
<img width="468" alt="image" src="https://github.com/user-attachments/assets/7740b810-da97-4a0a-9afa-664740b4d3b4">
The instance was then ready to use!
