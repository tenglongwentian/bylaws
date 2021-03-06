Carnegie Mellon University Student Senate Bylaws
================================================

Advantages
----------

- Simple, effective workflow for improvement and collaboration
- Complete history with extensive tooling
- Straightforward text format without pitfalls
- Easy conversion to a multitude of alternative formats
- Increased consistency and less room for errors

Dependencies
------------

To generate output files and lint files, the following development dependencies must be installed.

- make
- aspell
- pcregrep
- pandoc
- texlive-latex-base, texlive-fonts-recommended, texlive-latex-recommended, texlive-latex-extra

On Ubuntu-based systems, use `sudo apt-get install make aspell pcregrep pandoc texlive-latex-base texlive-latex-recommended texlive-latex-extra`.

Usage
-----

- Edit `bylaws.md`. Then, run `make` to generate DOCX, PDF and HTML outputs.
- Use `./lint.sh` to check for errors including misspellings, non-ASCII characters and trailing whitespace.
- Only propose changes to `bylaws.md` within pull requests. Always merge with rebase to ensure a linear history.
- Create a new tag and GitHub release with each bylaws content revision that includes voting details and date.
