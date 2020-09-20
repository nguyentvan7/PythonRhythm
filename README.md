# Python-based Rhythmic Pixel Simulator

## Sample folder structure and command
.
├── csv
│   └── frame-17.csv
├── input
│   ├── 1305031102.675285.png
│   ├── 1305031102.711263.png
│   └── 1305031102.743234.png
├── output
│   ├── 1305031102.675285.png
│   ├── 1305031102.711263.png
│   ├── 1305031102.743234.png
│   └── encoded
│       ├── 1305031102.675285.png
│       ├── 1305031102.711263.png
│       └── 1305031102.743234.png
├── rhythm_folder.py
├── rhythm.py
└── test.py

`$ python3 combined.py -i input -o output -r csv`

The output folder will be generated by the program. Note only 1 csv for 3 input frames. The first 2 frames will be considered as full frame captures. The last frame will get the regions applied. In general, if there are N frames and N-i csv files, then the last N-1 frames will have the regions applied, where as the first i frames will have full frame captures.
