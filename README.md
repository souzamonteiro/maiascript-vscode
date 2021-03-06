# MaiaScript Visual Studio Code Extension

Copyright (C) 2020 Roberto Luiz Souza Monteiro, Renata Souza Barreto, Hernane Borges de Barros Pereira.

This software is distributed under the terms of several open sources licenses.

Please read the files LICENSE, COPYING or COPYING.LIB for further information.

maiascript.js is a compiler that implements the MaiaScript programming language.

MaiaScript is a programming language aimed at developing adaptable and
intelligent applications. An adaptive application modifies its code to
suit the conditions of the environment. An intelligent application,
it learns to process the data it receives and adjusts to possible changes
in its characteristics, over time. The MaiaScript language implements the
adaptation paradigm, combining it with a variation of the object-oriented
paradigm, simplified to exclude definitions of types and access restrictions.
These characteristics make MaiaScript a programming language suitable for
rapid learning, both by Computer Science professionals and scientists who
are starting to implement computational algorithms. The characteristics of
this language, also allow the rapid development of complex applications,
especially when adaptability is necessary. MaiaScript also presents a syntax
similar to that used in Mathematics, including libraries for Numerical Calculation,
Complex Network Analysis, Database Access, Regular Expression Processing, and an
abstraction layer between the MaiaScript interpreter and the underlying Operating System.

The complete documentation, including the EBNF grammar file and the compiler's
syntax diagrams (railroad diagrams) can be found in the grammar directory.
For more information send mail to: [mailto:support@maiascript.com](mailto:support@maiascript.com)

## INSTRUCTIONS FOR USE:

To use the MaiaScript language in HTML documents, just include the
file "js/maiascript.js" in the document and insert the MaiaScript code
in `<script>` tags of type `"text/maiascript"`:

`<script type = "text/maiascript"> ... </script>`

To compile and run the scripts configure the page's onload event to execute
the "maiavm.compile()" method:

`<body onload = "maiavm.compile();" ... </body>`

To run MaiaScript code from the console, you need to install "Node.js" and the
npm packages "jsdom" and "websql". To run a script use:

`node js/maiascript.js "script name".maia`

Or, if you installed the MaiaScript compiler using npm:

`maiascript "script name".maia`

## INSTALL MAIASCRIPT VISUAL STUDIO CODE EXTENSION:

To install the MaiaScript Visual Studio Code extension use the command:

`npm install -g maiascript-vscode`

Or, get it from GitHub:

`git clone https://github.com/souzamonteiro/maiascript-vscode.git`

Or, download the latest zipped version:

`unzip maiascript-vscode-master.zip`

`cd maiastudio-vscode-master`

`npm install -g .`

Lauro de Freitas, September 2020.

Roberto Luiz Souza Monteiro
