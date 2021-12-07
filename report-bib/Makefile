.PHONY: typeset

FILES=`cat index.txt`

typeset:
	pandoc                          \
	  --from         markdown       \
	  --to           latex          \
	  --template     template_simple.tex   \
	  --out          report-bib.pdf \
	  --pdf-engine   xelatex        \
	  --bibliography "/Users/max/Notes/garden/_citations/Traffic_State_Estimation.bib"     \
	  --csl style.csl               \
	  --citeproc					\
	  "/Users/max/Notes/garden/Tasks/WIP/School/Optimal Control & Estimation Project.md" \
	  "./bibliography.md"