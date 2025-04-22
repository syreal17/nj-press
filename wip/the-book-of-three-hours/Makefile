# Makefile for building PDF with asciidoctor-pdf and custom theme

ASCIIDOCTOR_PDF=asciidoctor-pdf
SOURCE=book_of_three_hours.adoc
OUTPUT=book_of_three_hours.pdf
THEME=my-theme.yml

.PHONY: all clean

all: $(OUTPUT)

$(OUTPUT): $(SOURCE)
	$(ASCIIDOCTOR_PDF) -a pdf-theme=$(THEME) -o $(OUTPUT) $(SOURCE) && \
	cp $(OUTPUT) /mnt/c/Users/maran/Downloads/


clean:
	rm -f $(OUTPUT)

