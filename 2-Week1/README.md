# Week 1 lab: Feature transformation with Amazon SageMaker processing job and Feature Store

- [Setup the lab](https://labs.vocareum.com/web/1507942/419433.0/ASNLIB/public/docs/lang/en/README.md#id-l1section1)
- [Lab content: Configure dataset. Transform the dataset.](https://labs.vocareum.com/web/1507942/419433.0/ASNLIB/public/docs/lang/en/README.md#id-l1section2)
- [Finish the lab](https://labs.vocareum.com/web/1507942/419433.0/ASNLIB/public/docs/lang/en/README.md#id-l1section3)

------

## Setup the lab

*Note:* The lab uses Amazon Web Services (AWS) which take some time to spin up. You may need to wait a few minutes for the lab to open.

1. Click on ![img](../assets/images/posts/README/ButtonStartLab.png) button to begin the lab.

2. Click on ![img](../assets/images/posts/README/ButtonAWS.png) link (top left), which will open AWS Management Console.
   *Note:* If you see the window like in the following printscreen, click on **logout** link, close the window and click on ![img](https://labs.vocareum.com/web/1507942/419433.0/ASNLIB/public/docs/lang/en/lab_files/ButtonAWS.png) link again.

   ![image alt ><](../assets/images/posts/README/C1W1_AWSLogout.png)

3. Go to **Amazon SageMaker**.

   ![image alt ><](../assets/images/posts/README/C1W1_SageMaker.png)

4. Click on **Amazon SageMaker Studio**.

   ![image alt ><](../assets/images/posts/README/C1W1_SageMakerStudio.png)

5. Click on **Open Studio**. You may need to wait for a few moments and then hit a refresh button to see the **Open Studio** button.

   ![image alt ><](../assets/images/posts/README/C1W1_OpenStudio.png)

6. Wait a few moments...

   ![image alt ><](../assets/images/posts/README/C1W1_OpenStudioWait.png)

   ...welcome to SageMaker Studio.

   ![image alt ><](../assets/images/posts/README/C1W1_SMStudioWelcome.png)

   *Note:* If you do not see the SageMaker Studio screen shown above, you may need to disable pop up blockers and/or VPN.

7. Open System terminal.

   ![image alt ><](../assets/images/posts/README/C1W1_SystemTerminal.png)

8. Download the lab running the following command in the System terminal:
   *aws s3 cp --recursive s3://dlai-practical-data-science/labs/c2w1-487391/ ./*

   ![image alt ><](../assets/images/posts/README/C2W1_NotebookDownload.png)

   *Note:* You might need to update the environment to see the downloaded notebook.

   ![image alt ><](../assets/images/posts/README/C1W1_StudioUpdate.png)

9. Open `C2_W1_Assignment.ipynb` notebook (if you need to set the kernel, please choose "Python 3 (Data Science)").

   ![image alt ><](../assets/images/posts/README/C2W1_NotebookOpen.png)

## Lab content: Configure dataset. Transform the dataset.

1. Follow the lab instructions in the `C2_W1_Assignment.ipynb` notebook.

## Finish the lab

1. Click on ![img](https://labs.vocareum.com/web/1507942/419433.0/ASNLIB/public/docs/lang/en/lab_files/ButtonSubmit.png) button. To see the results of grading click on ![img](https://labs.vocareum.com/web/1507942/419433.0/ASNLIB/public/docs/lang/en/lab_files/ButtonGrades.png) button. You need at least 70 out of 100 score to pass! Click on ![img](../assets/images/posts/README/ButtonSubmissionReport.png) to review the test results and the feedback.

*Note:* If you want **to improve your score**, you can go back to the console, make changes and click on ![img](../assets/images/posts/README/ButtonSubmit.png) button again (the number of submissions is unlimited). Make sure that before the submission you run the last cell of the notebook, which uploads it to the S3 bucket. Then the changes will be taken into account for grading.

*Note:* The AWS account, which was created for the lab, **expires within 4 hours**. During this period you can close all of the console windows and come back to your work later. After the expiration the current AWS account will go through a cleanup procedure (which will take up to 25 minutes), then the access to the new account will take longer (up to 20 minutes) and your previous work will not be saved. **To save the notebook locally** before the expiration you can download the notebook from the Amazon SageMaker Studio (right click on the notebook -> “Download” command).

1. Close all the windows of the AWS Management Console.

