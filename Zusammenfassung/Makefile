all: automatisierungstechnik.pdf
	$(info ARTIFACTS:automatisierungstechnik.pdf)

.PHONY: automatisierungstechnik.pdf
automatisierungstechnik.pdf: automatisierungstechnik.tex ereignisdiskrete_systeme.tex multiagentensysteme.tex
	latexmk -pdf automatisierungstechnik.tex

.PHONY: clean
clean:
	latexmk -pdf -C
