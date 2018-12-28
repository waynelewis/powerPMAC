TOP=../..
include $(TOP)/configure/CONFIG
#----------------------------------------
#  ADD MACRO DEFINITIONS AFTER THIS LINE

#----------------------------------------------------
#  Optimization of db files using dbst (DEFAULT: NO)
#DB_OPT = YES

#----------------------------------------------------
# Create and install (or just install)
# databases, templates, substitutions like this
DB += powerPMAC_motor.template
DB += powerPMAC_controller.template
DB += powerPMAC_ai_int.template
DB += powerPMAC_ai_float.template
DB += powerPMAC_ao_int.template
DB += powerPMAC_ao_float.template
DB += powerPMAC_bi.template
DB += powerPMAC_bo.template

#----------------------------------------------------
# If <anyname>.db template is not named <anyname>*.template add
# <anyname>_TEMPLATE = <templatename>

include $(TOP)/configure/RULES
#----------------------------------------
#  ADD RULES AFTER THIS LINE

