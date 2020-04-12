```bash
subscription-manager register
subscription-manager list --available --all
subscription-manager attach --pool=pool_id
subscription-manager list --consumed
subscription-manager refresh
 
subscription-manager attach --auto
 
subscription-manager remove --all
subscription-manager unregister
subscription-manager clean
 
subscription-manager repos --list
 
subscription-manager repos --enable=rhel-6-server-optional-rpms
subscription-manager repos --disable=rhel-6-server-optional-rpms
```
