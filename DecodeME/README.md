## Testing DecodeME variants with AlphaGenome

- `batch_decodeme.ipynb` - Jupyter notebook which scores significant variants from the DecodeME study using AlphaGenome with the RNAseq scorer
- `gwas1_log10p_gt_7.tsv` - Variants from DecodeME with -log10p value >= 7.
- `variant-scores_rnaseq_decodeme_significant_all-tissues.csv.gz` - All scores returned by AlphaGenome. (~126 MB)
- `variant-scores_rnaseq_decodeme_significant_brain_protein-coding.csv.gz` - Only scores for brain expression of protein coding genes. (<1 MB)

To run the notebook, create a Python environment, install the packages in `requirements.txt`, and create a `.env` file in the same directory as the notebook with your AlphaGenome API key:

```
ALPHAGENOME_KEY=<Key Here>
```