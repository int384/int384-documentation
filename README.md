#### INT384

## Description
In this session, you will get hands-on with the <uicontrol>Cloud Integration Automation Service</uicontrol> (CIAS) to configure the integration scenario <uicontrol>Replicating Cost Centers from SAP S/4HANA On Premise to SAP SuccessFactors Employee Central</uicontrol> in an automated way. The scenario is part of the so called <uicontrol>Core Hybrid HCM</uicontrol> deployment option, which you can use to transfer your HR solutions to SAP SuccessFactors, yet keeping the cloud system integrated with your existing SAP S/4HANA system landscape.<br><br>
![](screens/Landscape.png)<br><br>

## Exercise

Run the following steps to complete the exercise:

Open the **INT384 Launchpad** in Google Chrome and  logon with your **INT384 user** (user + your number, e.g. USER01) and **Welcome19** as password.<br><br>
Click on the **Workflow Creation** tile.<br><br>
![](screens/CIAS-01.png)<br><br>
The **Create Workflow** application starts in a new browser tab.<br><br>
We have already pre-selected the **Integration Scenario** for this hands-on. Therefore simply click on the **Step 2** button to continue.<br><br>
![](screens/CIAS-02.png)<br><br>
On the **Integration Landscape** step, select **SFPART042584** as **SAP SuccessFactors Employee Central tenant** [1], **V0386** as **SAP Cloud Platform Integration tenant** [2] and **S4H** as **SAP S/4HANA On-Premise system** [3].<br><br> Finally click on the **Step 3** button [4].<br><br>
![](screens/CIAS-03.png)<br><br>
We are very interested in your role and knowledge about the products we use in this hands-on. So it would be very helpful for us if you could answer the questions below.<br><br>

> **NOTE**
>
> The "Experience Level" is optional. If you don't wont to share those levels, simply click on the Review button to continue.

<br>


Click on the **Review** button to continue.<br><br>
![](screens/CIAS-04.png)<br><br>
**Review** your selections on the **Summary** screen and click afterwards on the **Submit** button. The workflow will be **generated and activated** for your user (e.g. USER01).<br><br>
![](screens/CIAS-05.png)<br><br>
Once the **Workflow** is ready you will see a success message that the workflow is generated and available.<br><br>
Click on the **Cloud Integration Automation Service Inbox** link to start.<br><br>
![](screens/CIAS-06.png)<br><br>
**Congratulations, you have successfully created the workflow.**<br><br>
Please continue with the description in the **Cloud Integration Automation Service** (CIAS) to configure this integration scenario.<br><br>

## Important
Please observe the following notes when executing the workflow:<br>

#### Step: Confirm System Components
In the section **SAP SuccessFactors Provisioning**, please select the destination **SFSF_SFPART042584** from the **Assign Destination** dropdown.<br><br>
![](screens/CIAS-07.png)<br><br>
In the section **SAP Cloud Platform Integration**, please select the destination **CPI_V0386** from the **Assign Destination** dropdown.<br><br>
![](screens/CIAS-08.png)<br><br>

#### Automated Task Execution
Please ensure that you always execute the automation using the **Execute Step** [1] button, before you complete a task using the **Task Completed** [2] button.<br><br>
![](screens/CIAS-09.png)<br><br>

## License

This project is licensed under the SAP SAMPLE CODE LICENSE AGREEMENT except as noted otherwise in the [LICENSE file](LICENSE).
