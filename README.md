# Inflationary theory of branching morphogenesis in the mouse salivary gland. 
## I Bordeu, L Chatzeli and BD Simons. (2022)

### Content description:

This repository holds the raw data to reconstruct the branching trees of the salivary gland at E14.5, E16.5 and E18.5 for the control (n=3 biological repeat each), and for lobes 2 and 4 of the kras mice.

Each sample folder contains three files, whose content is described here:

**edge_list**: this file may be used to reconstruct the branching network, where each node corresponds to either a bifurcation or a endpoint. The file has 5 (control) or 3 columns (kras), where each row indicates a link (or a branch) in the tree. The columns, from left to right correspond to
| source node index | taget node index | branch length (microns) | outer duct width (microns, only in control) | inner duct width (microns, only in control) |.

**node_positions**: spatial location of each node in the edge_list file. The file has 4 columns corresponding to:
| node index | x-coordinate (pixels) | y-coordinate (pixels) | z-coordinate (pixels) |

**spatial_resolution_microns_per_pixel**: spatial resolution in microns per pixel/slice. The file has 3 columns:
| x-resolution | y-resolution | z-resolution |


