<!-- ╔══════════════════════════════ BEG ══════════════════════════════╗ -->

<br>
<div align="center">
    <p>
        <img src="./assets/img/logo.png" alt="logo" style="" height="80" />
    </p>
</div>

<div align="center">
    <img src="https://img.shields.io/badge/v-0.0.1-black"/>
    <img src="https://img.shields.io/badge/🔥-@minejs-black"/>
    <br>
    <img src="https://img.shields.io/badge/coverage----%25-brightgreen" alt="Test Coverage" />
    <img src="https://img.shields.io/github/issues/hmm-repos/lib?style=flat" alt="Github Repo Issues" />
    <img src="https://img.shields.io/github/stars/hmm-repos/lib?style=social" alt="GitHub Repo stars" />
</div>
<br>

<!-- ╚═════════════════════════════════════════════════════════════════╝ -->



<!-- ╔══════════════════════════════ DOC ══════════════════════════════╗ -->

- ## Quick Start 🔥

    > _**The simplest, fastest, most organized and stable way to build libraries and packages.**_

    - #### Setup

        > install [`hmm`](https://github.com/minejs-org/hmm) first.

        - ##### Create

            ```bash
            > hmm init <name> -t lib    # This will clone this repo and make some changes to suit your lib.
            > cd <name>                 # Go to the project directory
            > hmm install               # Install the dependencies
            ```

        - ##### Manage

            ```bash
            > hmm build         # To build your lib
            > hmm test          # To test  your lib
            > hmm lint          # To lint  your lib
            > hmm start         # To start your lib
            > hmm publish       # To publish on `npm`
            ```

        - ##### Fianlly

            ```bash
            # to install your library after publishing on `npm`
            hmm i {{tag}}
            ```

            ```ts
            // to import your library after installing via `hmm`
            import * as {{name}} from `{{tag}}`;
            ```

    <div align="center"> <img src="./assets/img/line.png" alt="line" style="display: block; margin-top:20px;margin-bottom:20px;width:500px;"/> <br> </div>

    - #### Structure

        - ##### Root

            ```bash
            ┣ assets
            ┃ ┗ ...            #  (logo.png, ..)
            ┃
            ┣ dist
            ┃ ┗ ...            # (index.js, index.js.map, ..)
            ┃
            ┣ src
            ┃ ┗ index.ts       # Main entry point
            ┃
            ┣ test
            ┃ ┗ index.test.ts  # Main test file
            ┃
            ┣ .env              # Environment configuration file
            ┗ .hmm              # Space configuration file

            # You can safely hide/ignore the rest of files.
            ```

<!-- ╚═════════════════════════════════════════════════════════════════╝ -->



<!-- ╔══════════════════════════════ END ══════════════════════════════╗ -->

<br>

---

<div align="center">
    <a href="https://github.com/minejs-org/hmm"><img src="https://img.shields.io/badge/by-hmm-black"/></a>
</div>

<!-- ╚═════════════════════════════════════════════════════════════════╝ -->