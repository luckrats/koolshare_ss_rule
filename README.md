fork from https://github.com/nu1ee/softcenter/tree/acelan_softcenter_ui/maintain_files
```bash
git clone --filter=blob:none --sparse  -b acelan_softcenter_ui https://github.com/nu1ee/softcenter.git
cd softcenter
git sparse-checkout set maintain_files
```
update
```bash
cd maintain_files/auto_update
./update_rules.sh
```
