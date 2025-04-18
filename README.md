# Double Threshold Validation Tool (DTVT)

### Code Author: Nicola Nocentini
### Contacts: nicola.nocentini@unifi.it, nicola.nocentini@gmail.com
===========================================================================

This repository contains the code implementation of the **Double-Threshold Validation Tool (DTVT)**, which is an automatic tool designed to validate pixel-based *Landslide Hazard Maps (LHMs)* and convert them into operational *Landslide Early Warning Systems (LEWSs)*.
DTVT is based on a pair of thresholds used to classify a spatial unit (or *Pixel Aggregation Units (PAUs)*, e.g., a catchment) as stable or not; which are:
##### -	*Failure Probability Threshold (FPT)*: the value of landslide probability value above which a pixel is considered unstable (e.g., ≥ 65%);
##### -	*Instability Diffusion Threshold (IDT)*: the amount of unstable pixels required to classify an entire PAU as unstable and to justify issuing a warning in that PAU (e.g., at least 5 pixels or 5% of the total pixels in the unit).
This approach also allows for establishing multiple warning criteria based on the FPT-IDT pair. By integrating DTVT into landslide hazard assessment workflows, decision-makers can effectively leverage LHMs for disaster risk reduction and emergency response.

You are encouraged to use this code with your own data. If you have any questions or require assistance, please don't hesitate to contact me.

**Workflow of the tool**

    
![Workflow_DTVT](DTVT/Code/Workflow_DTVT.jpg)
