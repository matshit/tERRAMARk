RECIPES := $(shell /bin/ls -A *.recipe)

all: $(RECIPES:.recipe=.mobi)

%.mobi: %.recipe
	eboo