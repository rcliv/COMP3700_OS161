VPATH = /root/cs161/cs161-gdb-1.5/./gdb-6.6+cs161/gdb/testsuite/gdb.threads
srcdir = /root/cs161/cs161-gdb-1.5/./gdb-6.6+cs161/gdb/testsuite/gdb.threads

EXECUTABLES = pthreads

all info install-info dvi install uninstall installcheck check:
	@echo "Nothing to be done for $@..."

clean mostlyclean:
	-rm -f *~ *.o a.out xgdb *.x *.ci *.tmp core* $(EXECUTABLES)

distclean maintainer-clean realclean: clean
	-rm -f Makefile config.status config.log config.h
