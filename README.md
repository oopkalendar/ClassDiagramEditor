# ClassDiagramEditor

<p align='justify'> 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This project deals with generator and editor of source code UML diagrams. It is a plug-in for Netbeans platform exclusively. Based on java files module is able to generate diagram of classes and packages, which we can further work with. During java files editing and saving, elements in diagram are modified while the original diagram form is preserved. After diagram modification, any changes are automatically reflected in java files too. The final diagram can be exported in form of picture or to XMI format.
</p>
## User´s Guide

### Install

<p align='justify'> 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Before the plug-in work starts, it is necessary to install this module. Installing the plug-in goes on as follows.
In the tools panel we choose the item Tools and we indicate the sub-item Plugins. The window that we can see in the picture number 1 opens, then ,  we choose the card Downloaded in it and  in the card we click on the button Add Plugins in the upper left corner. Then, we choose the install file  <a href="https://github.com/ClassDiagramEditor/ClassDiagramEditor/releases/download/1.0/org-fei-ClassDiagramEditor.nbm" target="_blank">.nbm</a> of the desired plug-in. In our case we enter the access way to the file org-fei-ClassDiagramEditor.nbm. After having it added, the module appears in the liste of the downloaded modules. Before the install, it is necessary to make sure that we have really indicated the module that we want to install. Then, we press the button Install in the bottom left corner. Besides, it is necessary to click away the warning windows informing us about the fact that the module is not registered and the user assumes responsibility for installing it. This way we can install each plug-in in the platform Netbeans.
</p>
<a href="https://github.com/ClassDiagramEditor/ClassDiagramEditor/releases/download/1.0/org-fei-ClassDiagramEditor.nbm" download>Download ClassDiagramEditor</a>
<br />

<div align="center"><img alt='Netbeans plug-in install' src ="/Images/picture1.png" /> </div>
<div align="center"> Picture 1 - Netbeans plug-in install </div>
<br />


### Uninstall

<p align='justify'> 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The similar way we installed the plug-in, we can uninstall it. We open the Plugins window again but this time we do not choose the card  Downloaded but Installed. It is situated just at the right of the card Downloaded. Then, we choose the module we want to uninstall. If we want to uninstall this specifis plug-in module, so we choose the module ClassDiagramEditor in the liste of installed plugins. In the upper right corner, there is the texte entry that facilitates us searching among all plug-in.  If we choose the plug-in, so there is the possibility of uninstalling in the bottom left corner – the button uninstall. It is also possible to deactivate the plug-in , if we want – using the button Deactivate.  
</p>
<br />
### The work with plug-in

<p align='justify'> 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;When the plug-in has been installed, the work with it can finally start. There are two ways we can start it up. The first one which is situated in the upper right corner , generates the diagram from the project, and it is indicated as the main one.The main project can be set up by clicking the folder Run as you can see in the Picture number 3.
If the mouse coursor points the Set Main Project , the opened projects appear. We choose the project we want to be the main one.
<br /><br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The second way is simpler and does not need the main project setting. You just click the right side mouse button on the project you want to generate the diagram from .
If you do so, all present alternatives available for the project appear. If you want to generate the diagram you choose from possibilities given in Generate Class Diagram, as it can be seen in the Picture number 2.
These are two ways how the generating of the diagram from the chosen project can start.
</p>
<br />
<div align="center"><img alt='Start plug-in' src ="/Images/picture2.png" /></div>
<div align="center">Picture 2 – Start plug-in</div>
<br /><br />
<div align="center"><img alt='Setting up the main project' src ="/Images/picture3.png" /> </div>
<div align="center"> Picture 3 - Setting up the main project </div>
<br />

<p align='justify'> 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;After having generated the diagram, you can continue working with the application. Picture n.4 you can see under the texte. We are going to use mainly the spots marked in red colour as it is easier to find and explain as well.
<br /><br />   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;We start in the left upper corner, when the section n.1 begins. By the means of this section, we can change the font size. The maximal font size is 18, the minimal one is 8. It is possible to change the font size by the means of buttons + and -.
<br /><br />  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;By the means of number 2 section, we can display or hide the in between classes associations. If we display the in between classes  associations, the sections 3 and 4 are interesting for us too. By the means of them, we can adapt the way of displaying these in between classes associations. If the associations are on, we can additionally put on displaying the attributes implementing the associations as well and if the displaying of these attributes is on, we can put the associations names off.
</p>
<br />

<div align="center"><img alt='Module operating' src ="/Images/picture4.png" /> </div>
<div align="center"> Picture 4  -  Module operating </div>
<br />

<p align='justify'> 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Number 5 section displays or hides constructors and number 6 section – if it is on – it displays diagrams in colour. If this section is off, they are displayed in black and white.
<br /><br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;There are 2 buttons right in the upper tool panel. The first one is Export XMI / section number 8 /, through which we get  diagram format XMI and in section number 9, there is Export Image, through which we get the diagram as the picture form.
<br /><br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The next is the right side panel which we use for the source file modifying thourough the diagram. At the top, there is section number 7, by the means of it we can delete the indicated element. The element is indicated by simple clicking. The indicated element is easy to be distinguished as the element edges are visibly highlighted. We can see the indicated element exemple also in the picture number 4 on the left. This indicated class influences directly the whole right side menu.
Under deleting, there is  another section – section number 10.Thtough this section we can add immerged classes.
On the other hand, in section 11 , we can adapt the element name. The last three menu sections on the right / sections number 12, 13 and 14 / are used for editing and variables or methods creating.
<br /><br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Section number 15 is the last one and it appears after right side mouse button clicking  e.g. on the package or class. It can add us other useful alternatives.
</p>

### Contact
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;classdiagrameditor@gmail.com
