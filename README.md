# The subjects of Tate

### In js_files:
- [1to2](./js_files/1to2.js): contains a mapping from the classes of the first level to the corresponding classes of the second level. To be used for obtaining the grids to display after clicking on the first level class.
- [id2url](./js_files/id2url.js): contains a mapping from the image name (used in all dictionaries as id) to the url where the image is hosted. To be used after the image id is sample at either level to access the url.
- [metadata](./js_files/metadata.js): contains all the metadata of each image accessed by image name. To be used for the 4th screen where the image is displayed alongside the metadata.
- [subj1id](./js_files/subj1id.js): contains the list of images belonging to each category at level 1. To be used to sample the images to show in each box of the grid in the homepage.
- [subj2id](./js_files/subj2id.js): contains the list of images belonging to each category at level 2. To be used to sample the images to show in each box of the grid of subclasses in the 2nd screen.
- len2display = {2:2, 14:(7,2), 3:3, 5:5, 9:(3,3), 21:(7,3), 10:(5,2), 6:6, 8:(4,2)} (how to create a grid based on the number of subclasses)
