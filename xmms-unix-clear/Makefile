SKIN_NAME = unix-clear
SKIN_FILES = README LICENSE Makefile \
	main.bmp balance.bmp cbuttons.bmp eq_ex.bmp eqmain.bmp \
	monoster.bmp nums_ex.bmp playpaus.bmp pledit.bmp text.bmp \
	posbar.bmp shufrep.bmp titlebar.bmp volume.bmp \
	pledit.txt viscolor.txt
CLEAN_FILES = *~ $(SKIN_NAME).tgz

.PHONY: all
all: skin

.PHONY: skin
skin: $(SKIN_FILES)
	GZIP=--best tar czf $(SKIN_NAME).tgz $(SKIN_FILES)

.PHONY: clean
clean:
	rm -rf $(CLEAN_FILES)
