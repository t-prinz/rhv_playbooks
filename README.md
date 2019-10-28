# rhv_playbooks
Playbooks for Red Hat Virtualization (RHV)

Add a host
ansible-playbook -i ../inventory prov_rhv_vm.yml -e "vm_fq_hostname=jws.aeronet.io" -e "rhv_vm_name=jws"

Remove a host
ansible-playbook -i ../inventory deprov_rhv_vm.yml -e "rhv_vm_name=jws"
