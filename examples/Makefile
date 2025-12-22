all: default.pdf rank.pdf no-id.pdf

clean:
	rm default.pdf; rm rank.pdf; rm no-id.pdf

default.pdf: test.csv
	yass -t Physicists -o default.pdf test.csv

rank.pdf: test.csv
	yass -t Physicists -o rank.pdf -T rank.tex test.csv

no-id.pdf: test.csv
	yass -t Physicists -o no-id.pdf -T no-id.tex test.csv