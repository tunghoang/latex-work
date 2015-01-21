.PHONY: all clean
all: syllabus.pdf

syllabus.pdf: syllabus.tex
	pdflatex $<

clean:
	rm -fr *.{aux,toc,snm,out,log,nav,dvi}
