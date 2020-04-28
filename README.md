# tiny-hypervisor

VMI (virtual machine introspection) (many of them support late launch)

[Windows only] blue pill / HyperDdg -> MoRE -> SimpleVisor -> hvpp / BareBone / HyperPlatform -> 
[Win+linux] ksm / BareFlank / iKGT / SecVisor 

Partition hypervisor:

Jailhouse (late launch) -> ACRN (type 1) 

Tee Hypervisor: 

InkTag -> OverShadow 

TrustVisor -> XMHF -> UberXMHF 

[0] hvpp: https://github.com/wbenny/hvpp

[1] iKGT: https://github.com/intel/ikgt-core

[2] HyperPlatform: https://github.com/tandasat/HyperPlatform

[3] SecVisor

[4] TrustVisor 

[5] Jailhouse 

[6] bareflank

[7] ACRN 

[8] SimpleVisor: https://github.com/ionescu007/SimpleVisor

[9] XMHF: https://github.com/uberspark/uberxmhf


Key contributors:

[1] Amit Vasudevan (CMU): https://uberxmhf.org/  (TrustVisor -> XMHF -> UberXMHF -> UberSpark)

[2] Assured Information Security (MoRE -> SimpleVisor -> HyperPlatform -> BareFlank)

