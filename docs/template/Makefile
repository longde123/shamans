../index.html: ../README.md prefix.html suffix.html
	cat prefix.html > index.html
	markdown ../README.md >> index.html
	cat suffix.html >> index.html
	mv index.html ../

.PHONY: clean

clean:
	rm -f ../index.html
