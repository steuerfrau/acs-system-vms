# Create Bibliography
latex system-vms.tex
bibtex system-vms.aux

# Compile Latex
latex system-vms.tex ; latex system-vms.tex

# Create PS file
dvips system-vms.dvi
