# gene4mVCF

## Introduction
`gene4mVCF` is a Python package that allows you to extract variant entries for specific genes or a list of genes from a VCF (Variant Call Format) file. It utilizes tools like `bcftools`, `tabix`, and Python libraries like `pysam`, `pandas`, `pybedtools`, `tqdm`, and `gffutils` to efficiently parse and extract variants.

## Installation

You can install `gene4mVCF` via pip:

`$ pip install gene4VCF`

## Usage
usage: `$ python3 gene4mVCF [-h] -i INPUT -g GENE`

Extract variant entries for a specific gene or list of genes from a VCF file.

optional arguments:
  -h, --help            show this help message and exit
  -i INPUT, --input INPUT
                        Input VCF file
  -g GENES, --genes GENES
                        Gene name, Ensembl gene ID, or path to a gene list file

## Examples
Extract variants for a single gene:
`$ python3 gene4mVCF -i input.vcf -g ENSG00000168878`

Extract variants for multiple genes listed in a file:
`$ python3 gene4mVCF -i input.vcf -g genes.txt`

For more options and details, refer to the help message.

## Support
For any issues or inquiries, please open an issue on the GitHub repository.

Make sure to replace `https://github.com/VJ-Ulaganathan/gene4mVCF` with your actual GitHub repository URL. You can customize the content further based on your preferences or additional information you want to include.


## Installation

You can install `gene4mVCF` via pip:

`$ pip install gene4mVCF`



