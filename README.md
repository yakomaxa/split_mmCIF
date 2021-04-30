# split_mmCIF
## Usage

```Rscript get_cif_and_split_into_chainPDB.R targetdir 1mbn 1a3n ```

-> This creates out directory named as split_chains and get 1mbn and 1a3n mmcif to split into split_chains

```Rscript split_bylist_cif.R listofciffile.txt ourputdir  ```

-> Pass list of cif files, then the script splits mmCIFs into chain PDB files in the outdir 

## License

GPL version 3 license. 

The license is after bio3d package because splitcif coems from pdbsplit in bio3d. 
