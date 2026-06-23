<img width="1920" height="1026" alt="image" src="https://github.com/user-attachments/assets/12374702-8acf-4137-a4bc-6ee74aa83c87" /># Bridging the Gap between Mathematics and Programming via a Dual-Target DSL for LaTeX and Haskell - Source Code

This repository contains a copy of the source files used for the research paper by "Niek Peters" titled "Bridging the Gap between Mathematics and Programming via a Dual-Target DSL for LaTeX and Haskell".

The paper uses the NBM prototype compiler with a custom setup for VSCode to compile a .nbm file to .tex and .hs files.

The VSCode setup uses the "LaTeX Workshop" and "Trigger Task on Save" extensions, to fully compile the source .nbm file to a .pdf file on save.

As the source includes evaluation sections, the setup relies on GHC being available on the system's PATH. 
During the writing process, the `texlive-full` package was installed on the system, providing support for LaTeX compilation and packages.
