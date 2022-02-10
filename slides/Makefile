MAIN=slides

all:
	latexmk -pdf -ps- -dvi- -recorder -shell-escape -interaction=nonstopmode $(MAIN).tex

clean:
	latexmk -c
	rm -f *.snm *.nav *.vrb *.synctex.gz
	rm -rf _minted-slides

FORCE:
