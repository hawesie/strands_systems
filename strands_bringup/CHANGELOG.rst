^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package strands_bringup
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.0.7 (2015-01-09)
------------------
* Include pc_monitor in robot bringup.
  Includes the now released pc_monitor in the strands_robot launch file.
* removing config for monitored nav (its already a default and it looks like it doesnt work)
* Contributors: Bruno Lacerda, Chris Burbridge

0.0.6 (2014-11-21)
------------------
* Make the subsampling parameters configurable.
* Same parameters as in movebase
* Contributors: Lucas Beyer, Nils Bore

0.0.5 (2014-11-20)
------------------
* Pass-through the EBC port for docking.
  DEFAULT TO NONE, ONLY ONE ROBOT HAS A LIGHT IN THERE.
  Feels good to shout once in the morning.
* Contributors: Lucas Beyer

0.0.4 (2014-11-19)
------------------
* Ability to include site-specific movebase parameters.
* Contributors: Lucas Beyer

0.0.3 (2014-11-19)
------------------
* Fixing argument rename
  This is wrong because both @nilsbore and me made PRs in parallel, so he didn't see my changes and I didn't see his.
* Update README.md
* Merge pull request `#91 <https://github.com/strands-project/strands_systems/issues/91>`_ from lucasb-eyer/hydro-devel
  Changes needed by `strands-project/strands_movebase#14 <https://github.com/strands-project/strands_movebase/issues/14>`_
* Added some more movebase parameters to strands_navigation
* Update to changes in strands_navigation/movebase
* Cleanup, while I'm at it.
* Contributors: Jaime Pulido Fentanes, Lucas Beyer, Marc Hanheide, Nils Bore

0.0.2 (2014-11-14)
------------------
* adding changes to launch files example start script and new strands_mapping and strands_ui launch files
* splitting strands_cameras from strands robot
* Fixing `#86 <https://github.com/strands-project/strands_systems/issues/86>`_
  Amidoinitrite?
* Contributors: Jaime Pulido Fentanes, Lucas Beyer

0.0.1 (2014-11-12)
------------------
* removing head user
* Update README.md
* Create README.md
* bug fixes
* Creating strands_bringup removing strands_bob, strands_linda, strands_rosie, strands_uol_sim and strands_wernee
* Contributors: Jaime Pulido Fentanes
