# bernmobil

This repository contains:
- a mapping and output file for the Canton data.
- a mapping and output files for Bernmobil ticket data (ZKDR and ZLST).

The mappings can be used for replicating the output files by using CARML. The CLI interface for CARML we developed, is able to use streams (https://github.com/netage/carml-cli).
To use this cli:

java -jar cli.jar -i input_file.xml -m mapping.ttl -o outputfile.ttl
