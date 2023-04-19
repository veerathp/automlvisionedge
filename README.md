# Vertex AI AutoML Vision Edge Workshop


## Setting up your environment for the workshop

**Step 1: Enable the Compute Engine API**

Navigate to Compute Engine and select Enable if it isn't already enabled. You'll need this to create your notebook instance.

**Step 2: Enable the Vertex AI API**

Navigate to the Vertex AI section of your Cloud Console and click Enable Vertex AI API.

![Enable Vertex AI API](/assets/images/enablevertexapi.png)

**Step 3: Create a Vertex AI Workbench instance**

From the Vertex AI section of your Cloud Console, click on Workbench:

![Workbench](/assets/images/workbench.png)

Enable the Notebooks API if it isn't already

![Notebooks API](/assets/images/notebooksapi.png)

Once enabled, click MANAGED NOTEBOOKS:

![Managed Notebook](/assets/images/managednotebook.png)


Then select NEW NOTEBOOK.

![New Notebook](/assets/images/newnotebook.png)


Give your notebook a name, and under Permission select Service account

![Create Notebook](/assets/images/createnotebook.png)

Select Advanced Settings.
Under Security select "Enable terminal" if it is not already enabled.
You can leave all of the other advanced settings as is.
Next, click Create.


Once the instance has been created, select OPEN JUPYTERLAB.
![Open Notebook](/assets/images/openjupyterlab.png)

Open the notebook and select the "TensorFlow 2(Local)" Kernel and follow notebook instructions

