# Viral GWAS Associations Explorer

Interactive web tool for exploring viral GWAS associations from the NHGRI-EBI GWAS Catalog. Upload your 23andMe, Ancestry, or Superkit genotype file to see your genetic risk profile for viral infections.

## Features

- **Multi-format genotype upload**: 23andMe, Ancestry, or Superkit formats
- **Real-time risk calculation**: Automatically calculates increased, partial, and protective risk categories
- **LD clumping**: Toggle between all SNPs or independent lead SNPs
- **Advanced filtering**: Filter by P-value, viral family, risk category, and search by SNP ID or gene

## Data Source

- NHGRI-EBI GWAS Catalog v1.0.2 (P-value ≤ 5×10⁻⁸, virus-related traits)
- LD clumping using 1000 Genomes Project reference data (multi-population)
- 317 viral GWAS SNPs, 134 independent lead loci

## Usage

Simply open `index.html` in a web browser. No installation required.

## Privacy

All data processing happens locally in your browser. Your genotype file is never transmitted to any server.

