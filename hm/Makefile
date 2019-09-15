BASENAME=hm
BUILDDIR=build

TEXNAME=${BASENAME}.tex
PDFNAME=${BASENAME}.pdf
JOBNAME=${BUILDDIR}/${BASENAME}

${PDFNAME}: ${TEXNAME} images/* figures/*.tex
	mkdir -p ${BUILDDIR}
	latexmk -pdf -jobname=${JOBNAME} ${TEXNAME}
	cp ${BUILDDIR}/${PDFNAME} ${PDFNAME}
