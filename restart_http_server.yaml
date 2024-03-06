---
- name: Restart service
  hosts: all
  tasks:
    - name: Debug service variable
      debug:
        var: service
 
    - name: Restart processes if not running
      shell:
        cmd: "systemctl start {{ service }}"
