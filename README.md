# Auto-Name
An example project to teach python tool scripting

# High Level Goals
- Append Lx_ (x >= 0) to all directories within specified root directory where X increases as directory traversal goes lower
- Append to all files the directory name found at L0. <directory name at L0>_

# Example Input
```
root_dir
|
└───folder1
│   │   file011.txt
│   │   file012.txt
│   └───subfolder1
│       │   file111.txt
│       │   file112.txt
│       │   ...
└───folder2
    │   file021.txt
    │   file022.txt
```

# Example Output
```
root_dir
|
└───L0_folder1
│   │   folder1_file011.txt
│   │   folder1_file012.txt
│   └───L1_subFolder1
│       │   subFolder1_file111.txt
│       │   subFolder1_file112.txt
│       │   ...
└───L0_folder2
    │   folder2_file021.txt
    │   folder2_file022.txt
```