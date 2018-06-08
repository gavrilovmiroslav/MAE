
all:
	rubber --pdf lambda-typing.tex && pdfcrop --margins 5 lambda-typing.pdf
	mv lambda-typing-crop.pdf lambda-typing.pdf
	rm -rf *.log *.aux
