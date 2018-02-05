# getDicomTarballs
Retrieve dicom tarballs from CFMM dicom server

# dicom2tar example:
singularity exec --bind /path/to/data:/data getDIcomTarballs.simg dicom2tar.py /data /data/output
