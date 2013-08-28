#
# Makefile for latex pdf generation.
#

all: report

report:
	rubber --inplace --maxerr -1 --short --force --warn all --pdf cv.tex

clean:
	rm -f *~ *.aux *.log *.toc *.blg *.bbl cv.pdf
