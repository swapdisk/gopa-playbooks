# Gopa Playbooks

This is a collection of Ansible playbooks that demonstrate how to automate RHEL7-8 in-place OS upgrades based on the [gopa-modules-rhel8](https://github.com/swapdisk/gopa-modules-rhel8) package.

The following playbooks are included:

- analysis.yml - Generates the Gopa preupgrade analysis report
- upgrade.yml - Creates LVM snapshots and launches the in-place OS upgrade
- rollback.yml - Undo the OS upgrade by performing LVM snapshot rollback
- commit.yml - Removes the LVM snapshots and cleans up

