open: ../cv.pdf
	if [ \"$${OSTYPE}\" != \"$${OSTYPE/darwin/}\" ] ; then open ../cv.pdf ; fi

../cv.pdf: cv.pdf
	cp cv.pdf ../cv.pdf

cv.pdf: cv.tex
	rubber --pdf cv

clean:
	rubber --clean cv
