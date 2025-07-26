# Sparse Attention Hub - Benchmark Results

This directory contains the source files for the GitHub Pages site showcasing benchmark results from the Sparse Attention Hub research project.

## Structure

```
docs/
├── index.html                           # Main landing page
├── micro_tests/                         # Benchmark artifacts
│   ├── metadata.tsv                     # Benchmark metadata (4.9MB)
│   ├── vector.tsv                       # Vector representations (1.8MB)
│   └── plots/                           # Interactive visualizations
│       ├── loogle_longdep_summarization/
│       │   ├── config_comparison.html   # Config comparison plots
│       │   ├── config_type_analysis.html # Config type analysis
│       │   ├── error_vs_density.html    # Error vs density analysis
│       │   └── layer_analysis.html      # Layer-wise analysis
│       └── longbench_passage_retrieval_en/
│           └── [visualizations coming soon]
└── README.md                            # This file
```

## Interactive Visualizations

The HTML files in the `plots/` directories are interactive visualizations created with Plotly. They allow researchers to:

- Zoom and pan through the data
- Hover over data points for detailed information
- Filter and explore different aspects of the results
- Export plots as images

## Data Files

- **metadata.tsv**: Contains benchmark configuration information, model parameters, and experimental settings
- **vector.tsv**: Contains vector representations and embeddings used in the analysis

## Usage

1. Visit the GitHub Pages site to view the interactive visualizations
2. Click on any visualization link to open the interactive plot
3. Use the plot controls to explore the data
4. Download raw data files for further analysis

## Technical Notes

- Large HTML files (4-17MB) may take time to load
- All visualizations are self-contained and don't require external dependencies
- The site is mobile-responsive and works on all modern browsers

## Contributing

To add new benchmark results:

1. Add new visualization files to the appropriate `plots/` directory
2. Update the `index.html` file to include links to new visualizations
3. Add corresponding data files to the `micro_tests/` directory
4. Commit and push changes to trigger automatic deployment

## Contact

For questions about the benchmark results or to contribute to the project, please visit the main repository: [sparse-attention-hub](https://github.com/[username]/sparse-attention-hub) 