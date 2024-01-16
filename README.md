# FSB PhD Thesis Template

This LaTeX template is designed for writing a PhD thesis at Faculty of Mechanical Engineering and Naval Architecture. It provides a structured format for organizing your research work and adheres to the guidelines set by the university.

## Disclaimer

This template is unofficial and is not approved or endorsed by the Faculty of Mechanical Engineering and Naval Architecture, University of Zagreb.

### Prerequisites

To use this template, you need a LaTeX distribution installed on your system.   

More details regarding latex installation can be found on the [link](https://milq.github.io/install-latex-ubuntu-debian/).
The template is tested on Ubuntu 22.04.3 LTS distribution.

## Structure 

The template is structured as follows:

- **`bib`**: This directory contains the BibTeX file.
- **`chapters`**:  Each chapter's text is stored in separate files within this directory. The main file, `thesis.tex`, utilizes the include command to incorporate each chapter.
- **`diagrams`**: This directory is dedicated to storing diagrams.
- **`figures`**: Place figures in this directory.
- **`settings`**: The settings directory houses the document's configuration files. Within this directory:
  - **`Package.tex`**: Controls the packages used in the document.
  - **`itlePage`**: Provides inputs for the title page.
  - **`customCommand.tex`**: A compilation of custom LaTeX commands.

## Acknowledgments

-  Special thanks to the original contributors for their effort in making the original version of this template. I'm not sure if the original version can be found online. I assume that the original author is Prof. Sanja Singer.
- Additional thanks to all other contributors who have contributed to this template.

---

### How to Contribute

If you would like to contribute, you can follow these steps:

1. **Fork the Repository**: Click the "Fork" button at the top right corner of this repository to create your copy. 
2. **Clone Your Fork**: Clone the repository to your local machine using the following command:    
   ```$ git clone https://github.com/your-username/your-forked-repo.git    ``` 
3. **Create a Branch**: Create a new branch to work on your additions:     
   ```$ git checkout -b fix-name    ```
4. **Edit Files**:  Make edits 
5. **Commit Your Changes**: Commit your changes with a descriptive commit message:    
   ```$ git add -u```   
   ```$ git commit -m "fix for ..."    ``` 
6. **Push to Your Fork**: Push your changes to your forked repository:     
   ```$ git push origin fix-name    ```
7.  **Create a Pull Request**: Open a pull request on the original repository. Once your pull request is reviewed it will be accepted or additional corrections will be asked. Thank you for contributing!

**Alternatively, you can make changes online** by following these steps:

1. Click on the "Edit On GitHub" symbol in the top-right corner of this page. This will bring you to the source code for this page on the GitHub repository.
2. Click on "Edit the file in your fork of the repository" (pencil symbol)
3. Add your work to the corresponding file.
4. Click on "Commit changes…" to commit these changes to your fork of the repository.
5. Click "Create a Pull Request" to request these changes.

If you have trouble with these steps, you can describe your problem by creating a new issue at https://github.com/iBatistic/FSB_PhD_thesis_template/issues
