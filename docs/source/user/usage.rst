How to Use
==========

The modules can be viewed pre-run on this site or run locally by downloading the Jupyter notebooks from the `GitHub repository <https://github.com/YangletLiu/quantum-education-modules>`_.

Students can explore any module freely. For those new to quantum computing, we offer example learning paths based on content from RPI courses to help guide your journey.

.. image:: ./images/learning_paths.png
   :align: center
   :class: custom-img

Each module is built using `Qiskit <https://qiskit.org/>`_, an open-source quantum computing framework developed by IBM. Qiskit allows users to build, simulate, and execute quantum circuits on real quantum hardware.

Running Locally
---------------

To run these modules on your local machine, follow the steps below:

1. **Clone the Repository**::

     git clone https://github.com/YangletLiu/quantum-education-modules.git
     cd quantum-education-modules

2. **Install Qiskit**

   Make sure you have Python 3.7 or higher installed. Then install Qiskit via pip::

     pip install qiskit

3. **Launch Jupyter Notebooks**::

     jupyter notebook

   Open any `.ipynb` file to interactively explore the content.

4. **(Optional) Connect to IBM Quantum Hardware**

   Some modules (such as Deutsch’s Algorithm or Grover’s Algorithm) can be executed on real IBM quantum computers. To use this feature:

   - Create an IBM Quantum account at https://quantum-computing.ibm.com/
   - Retrieve your API token from your profile.
   - Run the following inside a notebook to authenticate your session::

       from qiskit_ibm_runtime import QiskitRuntimeService
       QiskitRuntimeService.save_account("MY_API_TOKEN", overwrite=True)

Notes
-----

- Each module includes interactive code cells, visualizations, and conceptual explanations.
- The notebooks are self-contained and structured to progress from beginner to advanced topics.
- Prior experience with quantum computing is not required, but basic Python familiarity is recommended.