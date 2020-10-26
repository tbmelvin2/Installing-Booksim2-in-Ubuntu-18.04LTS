# Installing-Booksim2-in-ubuntu-18.04LTE
This repository contains files required to install booksim2. It works fine for me

The zip file is downloaded from this github repository
https://github.com/booksim/booksim2
Please be humble enough to refer their copyrights and give credits wherever possible.

STEPS FOR INSTALLATION
-----------------------
1. Extract and Go to src folder
2. open a terminal from that folder
3. Run
    > sudo make
4. Might need to install flex and bison
  > sudo apt-get install flex
5. Installing bison
  > sudo apt-get install flex bison
6. To run examples after successful installation use the example codes inside examples folder
    use the following command to run the torus88 example
    > ./booksim examples/torus88

