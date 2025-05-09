.. BAMT documentation master file, created by
   sphinx-quickstart on Thu Jan 19 21:13:42 2023.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to BAMT's documentation!
================================

The site contains documentation for the `BAMT framework <https://github.com/ITMO-NSS-team/BAMT>`__.

BAMT - Bayesian Analytical and Modelling Toolkit.
This repository contains a data modeling and analysis tool based on Bayesian networks.
It can be divided into two main parts -
algorithms for constructing and training Bayesian networks on data and algorithms for applying Bayesian networks for filling gaps,
generating synthetic data, assessing edges strength e.t.c.

.. image:: ../images/bamt_readme_scheme.png
   :target: ../images/bamt_readme_scheme.png
   :align: center

.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: Getting Started

   self
   getting_started/install.rst
   getting_started/contribution.rst
   getting_started/faq.rst
   getting_started/cite_us.rst


.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: API

   api/builders.rst
   api/mi_entropy_gauss.rst
   api/networks.rst
   api/nodes.rst
   api/preprocess.rst
   api/preprocessors.rst
   api/redef_HC.rst
   api/redef_info_scores.rst
   api/utils.rst

.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: Models

   models/bayesiannetworks/base_network.rst
   models/bayesiannetworks/discrete_bn.rst
   models/bayesiannetworks/continuous_bn.rst
   models/bayesiannetworks/composite_bn.rst
   models/bayesiannetworks/hybrid_bn.rst
   models/bayesiannetworks/sampling_predicting.rst
   models/bayesiannetworks/large_bn_algs.rst

.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: BN Theory

   bnalgs/bn_learning.rst
   bnalgs/big_bns.rst

.. toctree::
    :maxdepth: 1
    :hidden:
    :caption: Data
    
    data_section/data_management.rst

.. toctree::
    :maxdepth: 1
    :hidden:
    :caption: Examples, workflow pipelines

    examples/learn_save.rst
    examples/learn_params_vis.rst
    examples/read_structure_param_learning.rst
    examples/read_structure_and_params.rst
    examples/learn_sampling_predict.rst
    examples/add_ml_models_to_nodes.rst
    examples/composite_network_example.rst

.. toctree::
    :maxdepth: 1
    :hidden:
    :caption: Tutorials

    tutorials/tutorials_gists.rst



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
