.. _flow_enable:

-------------
Flow: Enable
-------------

Overview
++++++++

.. note::

  Estimated time to complete: 10-20 MINUTES

In this exercise you will enable Nutanix Flow and edit a blueprint within Calm that will be used to create an application that we will protect in the subsequent exercises.

Enabling Flow
++++++++++++++++++++++++++

Flow is built into Prism Central and requires no additional appliances or consoles to manage. Before you can begin securing your environment with Flow, the service must be enabled.

.. note::

  Flow can only be enabled once per Prism Central instance. If **Flow** displays a green check mark next to it, that means Flow has already been enabled for the Prism Central instance being used. Proceed to `Securing An Application`_.

In **Prism Central**, click the **?** drop down menu and select **Flow**.

.. figure:: images/10.png

Note that enabling Flow will require an additional 1GB of memory for each Prism Central VM, but there is no action required by the user as this occurs automatically.

Select **Enable Flow** and click **Enable**.

.. figure:: images/11.png

Takeaways
+++++++++

- Microsegmentation, part of Flow, is a decentralized security framework managed from Prism Central.
- Microsegmentation offers additional protection against malicious threats that originate from within the data center and spread laterally, from one machine to another.
- Once Flow is enabled in the cluster, VMs can be easily protected through Security Policies created in the Prism Central UI. These function as labels that can easily be applied to VMs without any additional network setup.
