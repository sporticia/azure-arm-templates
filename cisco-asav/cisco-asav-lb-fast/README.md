## arm-templates

This is the ASAv HA pair monolithic build template (no nested/linked templates, single file only)

**This version does not need storage accounts**

* Has x2 nodes (a and b)
* Uses managed disks
* No diags, so no need for storage account (slow to create/destroy)
* Includes Azure load balancer with probes for
