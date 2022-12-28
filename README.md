<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/fj-gruenewald/latex-templates-uhh/">
    <img src="img/doc.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Latex Templates</h3>

  <p align="center">
    University of Hamburg
    <br />
    <a href="https://github.com/fj-gruenewald/latex-templates-uhh/blob/main/README.md"> Readme </a>
    ·
    <a href="https://github.com/fj-gruenewald/latex-templates-uhh/releases"> Release </a>
  </p>
</p>

## How to write your Assignment


#### Insert your data
In the folder structure from the release you will find a definitions.tex file in which you only have to enter your data the rest happens all by itself, the type of elaboration, the title and your personal data will be added after filling in.

#### Start writing
In the main folder after unpacking you will find a folder called "content" in this folder there are several chapterX.tex files. These files represent the chapters of your work. Just start writing in chapter1.tex and after compiling it will be displayed in your work. If you want to add more chapters create a new "chapterX.tex" file then switch to assignment.tex and scroll down until you find individual chapters. Now you can load your chapter at the desired location using \input{content/chapterX.tex}

#### Add and use Acronyms
In the main folder you will find after unpacking a file with the name acronym.tex in which you can add more abbreviations. To add abbreviations just write between the \begin and \end tag an abbreviation with the following command: \acro{exa}[EXA]{Example} this command adds the abbreviation EXA for Example. To use an abbreviation in the text just write \ac{exa}. The first time the abbreviation is called it will be written out in full, after that only the short form will be used. You will find additional information in the file how to use the plural of abbreviations

#### Misc
how to reference things, do mathematical equations and create tables can be seen in the examples in the subfolder content in the file chapter2.tex

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

## Credit

Picture: [flaticon.com](https://www.flaticon.com/de/) by the User: [Freepik](https://www.flaticon.com/authors/freepik)
<br>
