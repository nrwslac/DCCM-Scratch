IOC_TOP = /reg/g/pcds/epics/ioc/common/ads-ioc/R0.6.1

IOC_INSTANCE_PATH := $(shell pwd)

# Set PRODUCTION_IOC to 1 to move from a testing to a production IOC:
PRODUCTION_IOC := 1

PROJECT_NAME := lcls-plc-rixs-optics
PROJECT_PATH := ../../lcls-plc-rixs-optics/lcls-plc-rixs-optics.tsproj
PLC := rixs_optics

PYTMC_OPTS := 
PREFIX := PLC:RIX:OPTICS

include $(IOC_TOP)/iocBoot/templates/Makefile.base
