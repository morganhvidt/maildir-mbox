maildir-mbox is a python script, it takes emails with folder structure maildir and converts them into a .mbox file. I use .mbox for moving/importing emails into an email program, like Mail OSX or Thunderbird.


To run, save as maildir-mbox.py and run:

$ python maildir-mbox.py [maildir_path] [mbox_filename]

E.g

$ python /folder/for/maildir-mbox.py /folder/of/mildir /path/to/new.mbox

[maildir_path] should be the the path to the actual maildir (containing new,
cur, tmp, and the subfolders, which are hidden directories with names like
.subfolde.subsubfolder.subsubsbfolder);
