obj-$(CONFIG_ARM64)	+=	cpu_ops.o
obj-$(CONFIG_QCOM_GSBI)	+=	qcom_gsbi.o
obj-$(CONFIG_QCOM_PM)	+=	spm.o
obj-$(CONFIG_MSM_RPM_SMD) +=	rpm-smd.o
ifdef CONFIG_DEBUG_FS
obj-$(CONFIG_MSM_RPM_SMD) +=	rpm-smd-debug.o
endif
obj-$(CONFIG_MSM_SMD)	+=	smd.o smd_debug.o smd_private.o smd_init_dt.o smsm_debug.o
obj-$(CONFIG_MSM_SMEM)	+=	smem.o smem_debug.o
obj-$(CONFIG_MSM_PIL) += peripheral-loader.o
obj-$(CONFIG_MSM_PIL_SSR_GENERIC) += subsys-pil-tz.o
ifdef CONFIG_MSM_SUBSYSTEM_RESTART
       obj-y += subsystem_notif.o
       obj-y += subsystem_restart.o
       obj-y += ramdump.o
endif
