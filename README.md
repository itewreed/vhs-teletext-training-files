# vhs-teletext-training-files
Additional trained files for teletext recovery

*Here you can find additional trained recovery pattern files for recovery of teletext.*

# How to use
Just copy the three files hamming.dat, parity.dat and full.dat into the vhs-teletext tool under ./vhs-teletext/teletext/vbi/data/\<videoformat\>/

Usually there is a folder called vhs, betamax, grundig_2x4. If you don't want to modify the code of vhs-teletext just use one of the three folders and overwrite the existing trained files in it. E.g., if you recover from vhs you probably don't need the training set of betamax and grundig, so put these new trained data there.

When deconvolving use the -f parameter and tell it to use the format where you've put in the new trained files.
