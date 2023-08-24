# THESIS-REPO-TITLE

**Bachelor's Degree Thesis in Computer Science**
<a href="https://www.overleaf.com/read/xdjkjrjcqyym">
    <img src=".github/assets/made-with-latex.svg" alt="Made with LaTeX">
</a>

<div style="display: flex; align-items: center;">
<img src=".github/assets/sapienza.png" height="60" style="background-color: #d2d2d2; margin-right: 16px;">
<img src=".github/assets/gyala.svg" width="170" style="background-color: #303030; max-height: 60px; ">
</div>

---

<a href="https://simonesestito.github.io/THESIS-REPO-TITLE/">
    <img src=".github/assets/thesis-button.svg" alt="Download Thesis">
</a>
<a href="https://example.com">
    <img src=".github/assets/presentation-button.svg" alt="Download Presentation">
</a>

This repository contains the LaTeX source of my thesis for the bachelor's degree
in Computer Science at "La Sapienza", University of Rome.

The thesis is written in Italian.

Available also on [Overleaf](https://www.overleaf.com/read/xdjkjrjcqyym).

**Note:**
Unfortunately the source code cannot be disclosed
because this exact thesis project will be used as
the foundation of a real project and internal tool in the company business.

However, you will be able to find **a lot of diagrams** in the PDF document and here in the [assets/](assets/) folder.

## PDF authenticity verification
You can download both the thesis PDF and the detached signature (`.sig` file), which can be verified using GPG.
It **must** be made with the same key I use for commits. In case I haven't changed it in the meanwhile, it should be [this one](https://github.com/simonesestito.gpg).

<details>
<summary>GPG key import and verification</summary>

```sh
git clone --depth=1 https://github.com/simonesestito/bachelor-thesis.git
cd bachelor-thesis/
curl -sSL https://github.com/simonesestito.gpg | gpg --import -
gpg --verify thesis.pdf.sig
```
</details>

## LICENSE

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

The *sapthesis* theme was made by [Francesco Biccari](https://biccari.altervista.org/c/informatica/latex/sapthesis.php) and it's obviously excluded by this license.

