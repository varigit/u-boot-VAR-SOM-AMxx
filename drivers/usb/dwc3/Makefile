ccflags-$(CONFIG_USB_DWC3_DEBUG)	:= -DDEBUG
ccflags-$(CONFIG_USB_DWC3_VERBOSE)	+= -DVERBOSE_DEBUG

obj-$(CONFIG_USB_DWC3)			+= dwc3.o

dwc3-y					:= core.o
dwc3-$(CONFIG_USB_DWC3_GADGET)		+= gadget.o ep0.o

obj-$(CONFIG_USB_DWC3_OMAP)		+= dwc3-omap.o
obj-$(CONFIG_USB_DWC3_PHY_OMAP)		+= ti_usb_phy.o
