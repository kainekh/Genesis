TARGET = gen-intro

all:
	pdflatex $(TARGET)
	biber $(TARGET)
	pdflatex $(TARGET)
	pdflatex $(TARGET)

clean:
	rm *.aux *.log *.pdf *.bbl *.bcf *.blg *.xml *.toc *.nav *.out *.snm
