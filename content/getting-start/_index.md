+++
title = "Getting started"
description = ""
weight = 1
alwaysopen = true
+++

New to Activity Creator Form? Or to Noctua in general? Well, you came to the right place: read this material to quickly get up and running.

## Activity Creator Form at a glance
What to read next

### What can you do with Activity Creator Form?
Create an activity, add an activity to an existing model and view activities in a models

With Activity Creator Form, you can create, add and view activities right in your web browser—no special software is required. Even better, multiple people can work at the same model, you can see people’s changes as they make them, and every change is saved automatically.
## 1. Creating an activity and its properties
To create new activities, launch a new browser tab with the Activity Creator Form

{{% panel theme="info" %}} In general, fill in as many fields as possible in the form, by typing in the field, and then selecting from the autocomplete suggestions by moving the mouse over your selection and clicking.
{{% /panel %}}

{{% alert info %}}**Tip**: In the autocomplete, enter a space after a complete word, to narrow down the choices.
{{% /alert %}}

### Step 1. Create Model Metadata

![](../images/create-model.png?classes=border,shadow)

a.	Enter a title for your model
b.	Select a model "state"
By default, all models begin in a "Development" state.
When ready, models may be moved to a "Production" state for publication by selecting "Production" from the drop-down list.
c.	Select an annotation group
Annotation groups are associated with curators in the users metadata file described above.
By default, the first group associated with your entry in the metadata file is the group listed in the form.
If you belong to multiple groups, you can select the appropriate group for your work from the drop-down list.

### Step 2. Create Annotations using the Function Description Form
Enter gene product or macromolecular complex to be annotated
By default, the form allows you to enter a single gene product. Start typing, choices will appear, and then select the gene product.

{{% alert info %}}
**Tip:** You can type in the gene symbol, e.g. Wnt3a or the unique identifier or accession, e.g. UniProtKB:P56704. If necessary to narrow down the choices, type a space after the symbol, and enter the three letter code for the species (first letter from genus and two from species name, e.g. mmu for Mus musculus).  Each entry in the autocomplete will also show the associated unique database identifier or accession, so curators can confirm that they are selecting the appropriate entity for annotation.
{{% /alert %}}
 Enter the molecular function, evidence, and reference
These fields are required. If you fill in the first field of any line, you need to add evidence and a reference.
If the Molecular Function is known, enter the appropriate GO term, evidence code and reference.
If the Molecular Function is unknown, but you are also making a Biological Process annotation, enter "molecular_function" and the same evidence and reference as the Biological Process annotation.
If the Molecular Function is unknown, and there is no evidence for what the Molecular Function might be, enter "molecular_function" and the ND evidence code.
Enter other fields (optional)
For Molecular Function, the following "extensions" can optionally be added:
has_input(molecule): fill in the "has input" field, evidence, and reference.
happens_during(biological phase): fill in the "happens during" field, evidence, and reference.
In addition, curators can add annotations to:
Biological Process (the form assumes a part_of relation between the Molecular Function and Biological Process)
Additional BP part_of "extensions" can be made to provide contextual information to the BP term.
Cellular Component (the form assumes an occurs_in relation between the Molecular Function and Cellular Component)
Additional part_of "extensions" can be made to provide contextual information about cell and/or tissue type.
We recommend that you fill in as many fields as possible before creating the activity, as after it is created, you will need to edit it from the graph canvas, which requires more steps to do.
### Step 3. Add the new activity to a model
Press the CREATE button. A new activity will appear on the graph canvas (the main window).

Tips:
1. Each new activity will appear on the same part of the canvas, so if you add more than one activity you will need to move them around on the canvas (by clicking and dragging) to see the ones underneath.
2. If the CREATE button is grayed-out, there is some information missing from the form that you still need to fill in.  You can press the "why is the save button disabled?" for a list of missing fields.



## Requirements

Download [Hugo binary](https://gohugo.io/overview/installing/) for your OS (Windows, Linux, Mac) : it’s that simple

{{%children style="h2" description="true"%}}
