all: slides.pdf

%.pdf: %.tex
	pdflatex $<
	pdflatex $<

clean:
	rm -f *.aux *.log *.nav *.out *.snm *.toc *.vrb
	rm -f slides.pdf
