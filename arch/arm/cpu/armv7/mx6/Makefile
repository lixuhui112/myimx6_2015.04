#
# (C) Copyright 2000-2006
# Wolfgang Denk, DENX Software Engineering, wd@denx.de.
#
# (C) Copyright 2011-2015 Freescale Semiconductor, Inc.
#
# SPDX-License-Identifier:	GPL-2.0+
#

obj-y	:= soc.o clock.o
obj-$(CONFIG_SPL_BUILD)	     += ddr.o
obj-$(CONFIG_SECURE_BOOT)    += hab.o
obj-$(CONFIG_MP)             += mp.o
ifdef CONFIG_MX6UL
obj-$(CONFIG_CMD_BEE)        += bee.o
endif
obj-$(CONFIG_MODULE_FUSE)        += module_fuse.o
