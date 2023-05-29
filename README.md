Simple repo for ArgoCD to sync from on initial cluster install/bootstrap. 

This approach would be:
Ansible install of ARO:
 -> Ansible bootstrap of GitOps Operator
    -> Ansible apply first ACD Application. 
---> You are here. 
