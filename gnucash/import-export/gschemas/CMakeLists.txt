
SET(generic_import_GSCHEMA org.gnucash.dialogs.import.generic.gschema.xml)

add_gschema_targets("${generic_import_GSCHEMA}")

SET_DIST_LIST(generic_import_gschema_DIST CMakeLists.txt Makefile.am org.gnucash.dialogs.import.generic.gschema.xml.in.in)
