all: 
	@if `which xdelta > /dev/null 2>&1`; then \
		xdelta patch patch/nds2dat.patch in/*.nds out/out.dat; \
	else \
		echo "Xdelta is not installed!"; \
	fi
clean:
	rm -rf out/*
