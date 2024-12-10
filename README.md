# ReDroid Kernel Modules For Openwrt

- Optional Modules

```bash
#add to config-6.6:
CONFIG_ASHMEM=y
CONFIG_ION=y
CONFIG_ION_SYSTEM_HEAP=y
CONFIG_ION_CMA_HEAP=y
```

test in kernel-6.6

forward port ion(5.10) & ashmem(5.15)
