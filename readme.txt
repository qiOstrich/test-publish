*This is ReadMe file, your dataset directory does not need contains this file.*
*Directory dataset_dir/<lang> is your dataset base directory.*
*All text base file must be unix format.*

Note: <lang> can be zh or en

Directory zh
 - Store chinese dataset for training and validation

Directory en
 - Store english dataset for training and validation

File <lang>/training.tsv
 - Store text samples for training.
 - Fields split by tab.
 - Columns: label, content
    No column header, first line is data.
    ‘label’ must be string, cannot include space.
    ‘content’ must be string, can include space.

File <lang>/validation.tsv
 - Store text samples for validation.
 - Fields split by tab.
 - Columns: label, content
    No column header, first line is data.
    ‘label’ must be string, cannot include space.
    ‘content’ must be string, can include space

