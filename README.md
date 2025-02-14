
# The Virtual Brain

"The Virtual Brain" Project (TVB Project) has the purpose of offering 
modern tools to the Neurosciences community, for computing, simulating
and analyzing functional and structural data of human brains, brains modeled 
at the  level of population of neurons.

### TVB Core 

To **install** locally TVB code on your machine, we recommend you to first create a dedicated 
 Python env, and afterwards to take our main Pypi released packages:

        pip install tvb-library
        pip install tvb-framework
   
Alternatively and easier, you could simply download **TVB_Distribution** from:
<https://www.thevirtualbrain.org/tvb/zwei/brainsimulator-software>. In this
variant, you will have Python, TVB and all our 3rd party dependencies downloaded together, 
you do not need to do anything else other than unzip and double click on **tvb_start** command.

More details on our documentation site: <http://docs.thevirtualbrain.org>.

Source code available here: <https://github.com/the-virtual-brain/tvb-root>
     
   
### TVB NEST 

Integration between TVB and NEST, for multiscale (co)simulations .

Source code available here: <https://github.com/the-virtual-brain/tvb-multiscale>

### TVB Data

Both tvb-library and tvb-nest might need at some point some TVB compatible data.
We have published our latest dataset here: https://zenodo.org/record/3688773#.XskDMp4zZYg.
Download, unzip and execute:

    python setup.py install

We also have an older (and much smaller dataset) under Pypi, but remember this is a 
subset of what can be found on Zenodo link above:

    pip install tvb-data

# Relevant TVB Resources

- For issue tracking we are using Jira: http://req.thevirtualbrain.org
- For API documentation and live demos, have a look here: http://docs.thevirtualbrain.org
- A public mailing list for users of The Virtual Brain can be joined and followed 
  using: tvb-users@googlegroups.com
- Raw demo IPython Notebooks can be found under: 
  https://github.com/the-virtual-brain/tvb-root/tree/master/tvb_documentation/demos


# Acknowledgments

This project has received funding from the European Union’s Horizon 2020 Framework Programme for Research and Innovation under the Specific Grant Agreement Nos. 785907 (Human Brain Project SGA2), 945539 (Human Brain Project SGA3) and VirtualBrainCloud 826421.
