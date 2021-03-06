============================================
The Trajectory, Single Runs and Group Nodes
============================================


----------------
Quicklinks
----------------
Here are some links to important functions:

.. currentmodule:: pypet


.. autosummary::
    :nosignatures:

    ~trajectory.Trajectory
    ~trajectory.SingleRun
    ~naturalnaming.ParameterGroup.f_add_parameter
    ~naturalnaming.DerivedParameterGroup.f_add_derived_parameter
    ~naturalnaming.ResultGroup.f_add_result
    ~naturalnaming.NNGroupNode.f_iter_leaves
    ~naturalnaming.NNGroupNode.f_iter_nodes
    ~naturalnaming.NNGroupNode.f_get
    ~trajectory.Trajectory.f_explore
    ~trajectory.Trajectory.f_load
    ~trajectory.Trajectory.f_update_skeleton
    ~trajectory.Trajectory.f_preset_parameter
    ~trajectory.Trajectory.f_get_from_runs
    ~trajectory.SingleRun.f_load_items
    ~trajectory.SingleRun.f_store_items
    ~trajectory.SingleRun.f_remove_items
    ~trajectory.SingleRun.f_delete_items
    ~trajectory.Trajectory.v_idx
    ~trajectory.SingleRun.v_standard_parameter
    ~trajectory.SingleRun.v_standard_result
    ~naturalnaming.NNGroupNode.v_annotations



--------------------
Trajectory
--------------------
.. autoclass:: pypet.trajectory.Trajectory
    :members:



-------------------
SingleRun
-------------------
.. autoclass:: pypet.trajectory.SingleRun
    :members:


-------------------
NNGroupNode
-------------------

.. autoclass:: pypet.naturalnaming.NNGroupNode
    :members:
    :inherited-members:


-------------------
ParameterGroup
-------------------

.. autoclass:: pypet.naturalnaming.ParameterGroup
    :members:


-------------------
ConfigGroup
-------------------

.. autoclass:: pypet.naturalnaming.ConfigGroup
    :members:

-----------------------
DerivedParameterGroup
-----------------------

.. autoclass:: pypet.naturalnaming.DerivedParameterGroup
    :members:

-------------------
ResultGroup
-------------------

.. autoclass:: pypet.naturalnaming.ResultGroup
    :members:

