Some Ubuntu packages like `latexmk` depend on `texlive-latex-base`. Installing it would conflict with a manually installed TeX distribution (like the more recent releases of TeX Live using their installer).

This is a trivial empty package generated using `equivs-build` which satisfies these dependencies without installing TeX through the system package manager. Simply install [this .deb](https://github.com/neapel/ubuntu-fake-texlive/blob/master/fake-texlive_1.0_all.deb?raw=true).
