
SUBDIRS = polkit polkitbackend polkitagent programs

if BUILD_EXAMPLES
SUBDIRS += examples
endif

clean-local :
	rm -f *~

-include $(top_srcdir)/git.mk
