# MLFeatsMerger
Merging two feature files based on matching first column

*This is for my personal usage only. If you think, it is useful for you, you can use it with little modification.*

This bash file takes three 4 files (3 features + 1 target) file and generates a perfect ML dataset. For more information, look at the example. This example won't work for you (for sure). This bash script also does some serious amount of preprocessing before making the files concatenata-ble.

If you are a Unix (Shell) scripting guy, you should be able to figure out easily what is this file doing.

## v1: update

The v1 does not store the intermediate files in the current directory. It keeps them in the /tmp/ directory and then clears the /tmp/ directory for better management. The output is only the two files: train.txt and test.txt which are perfect for learning Ml models. The first column is just the name (must not be used as a feature).
