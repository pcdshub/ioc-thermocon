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
DB += thermocon.db

DB_INSTALLS += $(AUTOSAVE)/db/save_restoreStatus.db
DB_INSTALLS += $(IOCADMIN)/db/iocSoft.db

#----------------------------------------------------
# Create and install (or just install)
# Archive files, templates, substitutions like this
#
ARCHIVE += thermocon.archive

#----------------------------------------------------
# Create and install (or just install)
# Autosave request files, templates, substitutions like this
#

REQ += thermocon.req

include $(TOP)/configure/RULES
#----------------------------------------
#  ADD RULES AFTER THIS LINE

