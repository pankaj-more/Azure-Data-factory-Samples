<h1>Copy files between azure blobs</h1>
The data factory pipeline'copy-blob-adf-101' caters the simple scenario of copying files between different blobs. After copy cleanup the files from the source blob.
Below activities are performed:
  - Copy files from 'input' blob with linked service 'inoundBlob' to 'output' and 'output3' blobs.
  - Delete the file from source 'input' blob after copy
