
SUBDIRS = src

hitch.8: hitch.man.rst
	${RST2MAN} --halt=2 $(srcdir)/hitch.man.rst $@

doc_DATA = hitch.conf.example CHANGES.rst README.md

dist_man_MANS = hitch.8

EXTRA_DIST = LICENSE README.md hitch.man.rst hitch.conf.example CHANGES.rst docs
