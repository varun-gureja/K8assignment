# K8assignment - Below are the observations found while working on the Voting App
After deleted the voting pod, observed that another new voting pod got created. Voting portal and Result apps were working successfully.
After deleted the worker pod, observed that another new worker pod got created and voting portal was still working and result was success.
After deleted the db pod, observed that another new db pod got created and voting portal was still working but result portal was not showing the older results and also new votes.
Since the data in the db was not backed up the older results cannot be retained.
DB pod data mount path was not available in worker node after db restart.
Result pod was restarted. voting and result app were working fine.
