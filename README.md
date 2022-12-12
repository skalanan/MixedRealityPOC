# MixedRealityPOC

Currently we are working on a project where we have to integrate a multi-user functionality to an existing HoloLens app. We used PUN so that we can see other users interactions and wanted to use Azure spatial anchors so that the coordinates will be shared across all users as well. We followed the Microsofts’s Azure Spatial Anchors tutorial [1] to configure the buttons and to connect the scene to an Azure resource. 

To test it we used 2 HoloLenses. On one, we were able to start an Azure session, create an anchor and share it. On the other, as we click on the “get anchor” button, it shows on the debug console that the anchor was updated successfully, even though the object is still in the same position and hasn’t been updated. Do you know where the problem lies at and what could be done so that the objects / anchors will be actually updated?

As a minimal example, we provide you our Proof-of-Concept, which allows multiple people interact with each other (same as the example described above). 

# SetUp
* Clone this repo
* open files with Unity
* drag Sample Scence in Assets -> Scences -> Sample Scence into the hierarchy

[1] https://learn.microsoft.com/de-de/training/modules/azure-spatial-anchors-tutorials/
