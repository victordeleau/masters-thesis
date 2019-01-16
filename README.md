# master's thesis backbone

To fill according to your needs.

I made the wrapper script **pdflatex_clean** to compile latex files to pdf using **pdflatex** and then move all the boring auxiliary files (.aux / .log / .out / etc) into the aux/ folder. If you experience problems with this script try a bigger value in front of the sleep command. On Linux to call it in the terminal, place the script in **/usr/local/bin** and execute **sudo chmod +x /usr/local/bin/pdflatex_clean)** to make it executable.

This master's thesis backbone has a tree structure. You can compile chapters or even files independently, which might be useful if your project is large.