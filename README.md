# Phabricator-maintenance-bot
Source for https://phabricator.wikimedia.org/p/Maintenance_bot/

* `column_mover.py` is a script that can move columns of a task when some actions happens on it. E.g. Moving a task in workboard #user-ladsgroup from column "incoming" to column "done" when someone changes the task's status to "done"
* `patchforreview_remover.py` is an automatic script that removes the "patch_for_review" tag when all patches have been merged or abandoned
