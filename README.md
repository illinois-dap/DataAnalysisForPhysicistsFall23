# Data Analysis for Physicists (PHYS 398 DAP)

All instructions, including creating a simple book, and referenes can be found at https://jupyterbook.org

## Create a template book
`jupyter-book create IntroComputationalPhysics`

## Build the book to make the html
`cd IntroComputationalPhysics`
### For solutions version
`jupyter-book build --config _config.yml --toc _toc_wSoln.yml ./`
### For student version
`jupyter-book build --config _config.yml --toc _toc.yml ./`

## Clean the build
`jupyter-book clean ./`

## Copy to illinois course server (MacOS with course server mounted)
```
cd ~/repos/illinois-dap/DataAnalysisForPhysicists`
cp -rp ./_build/html/* /Volumes/phys398dap/fa2023/secure/html/
```
