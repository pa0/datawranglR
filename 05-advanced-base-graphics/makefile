all: multi par

multi: 
	Rscript -e "knitr::knit('multipanel-notes.Rnw')"
	pdflatex multipanel-notes

par:
	Rscript -e "knitr::knit('par-notes.Rnw')"
	pdflatex par-notes

clean:
	rm *.tex
	rm -rf *.log *.bbl *.blg *.out *.toc *.aux *.fdb_latexmk *.fls
