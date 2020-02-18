# LaTeX configuration 

1. Download MikTeX from the official site https://miktex.org/2.9/setup.
   Optionally a distribution such as BasicTeX or TeXLive could be installed (in case of lack of space), but it      is recommended to download the MikTeX if possible. After downloading, perform the installation.

![MikTeX](img/miktex.png)

2. Download and install the TeXmaker program from the official site 
   https://www.xm1math.net/texmaker/download.html.

3. To check if everything was installed correctly, open the TeXmaker program and select File -> New. Copy and       paste below code:


```python
\documentclass[12pt,a4paper,openany]{article}

\begin{document}

Hello world.

\end{document}
```

4. Save the file under the hello_world.tex name and select "Quick Build" option from the menu above the file        code. Make sure that the "View PDF" option is enabled next to the build option. Running the build should         result in creating .pdf file and previewing it in the program.

![hello_world](img/hello_world.png)
