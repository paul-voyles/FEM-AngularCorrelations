[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/CSSFrancis/FEM-AngularCorrelations/HEAD)

Introduction
-------------
This notebook walks through how to perform fluctuation electron microscopy (FEM) and correlation symmetry coefficient analysis using hyperspy/pyxem.  The workflow might change slightly with 
time but for now it works, it is fairly fast, and it can accomplish most of the things necessary for these types of experiments.

If you are interested or need further instrucution then you can always contact csfrancis@wisc.edu for
additional support.  Before doing so please read through any documentation provided etc. 

Installation (Hyperspy/PyXEM)
-------------------------------
***Downloading:*** To download any packages that might be necessary the best thing to do is to install the [Hyperspy-Bundle](http://hyperspy.org/hyperspy-doc/current/user_guide/install.html) Which should handle installing pyxem and hyperspy.  Alternitavely you can download both pyxem and hyperspy individually using pip or anaconda. [Hyperspy-install](http://hyperspy.org/hyperspy-doc/current/user_guide/install.html) [pyxem-install](https://github.com/pyxem/pyxem-demos)


***Launching a Jupyter Notebook:*** To launch a jupyter notebook from the bundle you should run the Miniforge Prompt (Hyperspy-bundle) application.

![bundle_test_qtconsole](https://user-images.githubusercontent.com/41125831/131411715-98a67a0f-3c16-4d78-9e21-f92b9caeb950.png)

Then run the commoand $jupyter notebook to start a notebook server.   You can also right click on a directory and the option "Jupyter Notebook Here" should be available. You can then open up the notebook you are interested in running. 


![Jupyter notebook](https://user-images.githubusercontent.com/41125831/131411980-1193eb8a-8324-4dcf-9997-eaa5cf57069a.PNG)

![Jupyter notebook2](https://user-images.githubusercontent.com/41125831/131412142-fe1a164d-df16-4d54-8316-fb31bf132e00.PNG)

***What the Bundle Includes:*** The bundle will download a couple of different python programs which are useful in analyzing electron microscopy data:
- ase (For atomic simuations)
- atomap (HRTEM studies)
- HyperSpy (High dimensional Analysis)
- HyperSpyUI (Hyperspy in a GUI format!) To launch the GUI you can launch th Hyperspy-UI(hyperspy-bundle)
- LumiSpy (luminecense spectroscopy)
- kikuchipy (kikuchi diffraction)
- particlespy (segmenting particles)
- pystackreg (image allignment
- pyxem (4-D STEM)
- nglview (Viewing Molecular Structures)
- scanning_drift_corr (Drift Correction)

***Note:*** if you already have a version of python or anaconda on your computer then this will install a second version of python. Make sure you are using the hyperspy bundle distribution or download pyxem/hyperspy using pip or conda as described above


Using Git to clone this Repo
-------------------------------

To clone this repository you can use the command:

`$ git clone https://github.com/CSSFrancis/FEM-AngularCorrelations.git`

as long as you have git installed on your computer -- [Git installation](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

Binder Link
------------
If you want to play around with things first before downloading anything the binder link above will bring you to a preconfigerd environment you can run remotely rather than on your personal computer

This will be quite a bit slower, but still might be useful
