## What this command does:

#### This command accepts a file (filename,DueDate)
#### checks the files and their due date
#### moves the files which are over due (7 days) and next due (7 days) to a new directory



## Why/When this command is useful:

#### Useful for file managment
#### useful for file organization
#### prevents file name duplication


 
## How to use the command:

#### To use this command the user will first need
#### 1. File called filelist (format: filename,YYYY-MM-DD)
#### 2. Run this command in the same directory where the files exist



## Examples:


### Step 1:
    [fatemasu24@sjsu samplefiles]$ ls

    file1    file11   file125  file14  file200  file3   file33   file40   file56  file67   file77   file88   file91  filelist

    file10   file110  file13   file2   file204  file31  file355  file405  file59  file68   file777  file880  file94  Due

    file101  file123  file131  file20  file295  file32  file4    file5    file6   file680  file80   file90   file99



### Step 2:
    [fatemasu24@sjsu samplefiles]$ ~/files/samplefiles/Due

    Moved 'file1' to '/mnt/scratch/fatemasu24/Due'.

    Moved 'file2' to '/mnt/scratch/fatemasu24/Due'.

    Moved 'file3' to '/mnt/scratch/fatemasu24/Due'.

    Moved 'file5' to '/mnt/scratch/fatemasu24/Due'.

    Moved 'file10' to '/mnt/scratch/fatemasu24/Due'.

    Moved 'file125' to '/mnt/scratch/fatemasu24/Due'.

    Moved 'file880' to '/mnt/scratch/fatemasu24/Due'.

    Moved 'file405' to '/mnt/scratch/fatemasu24/Due'.



### Step 3:
    [fatemasu24@sjsu samplefiles]$ ls

    file101  file110  file13   file14  file200  file295  file32  file355  file40  file59  file67  file680  file777  file88  file91  file99 

    Due file11   file123  file131  file20  file204  file31   file33  file4    file56  file6   file68  file77   file80   file90  file94  filelist



### Step 4:
    [fatemasu24@sjsu a2]$ cd ~/Due/

    [fatemasu24@sjsu Due]$ ls

    file1  file10  file125  file2  file3  file405  file5  file880
