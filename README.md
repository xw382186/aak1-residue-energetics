# AAK1 residue-resolved energetics: scientific data and analysis code

Scientific source-data companion for *Residue-Resolved Energetics Complement AI Ranking for Adaptor-Associated Kinase 1 Hit Selection*.

Repository: [https://github.com/xw382186/aak1-residue-energetics](https://github.com/xw382186/aak1-residue-energetics).

## Download the deposited files

- [Data_Code.zip](Data_Code.zip): numerical source data, all nine numbered workbooks, laboratory originals, accepted result exports and scientific code (299 files).
- [Figures_SI.zip](Figures_SI.zip): original five main PDF/TIFF figures and nineteen supplementary PDFs with figure provenance (30 files).

Extract both archives in the same directory to obtain the directory structure described below. `ARCHIVE_CONTENT_MANIFEST_SHA256.csv` gives per-member sizes and SHA256 hashes; `UPLOAD_MANIFEST_SHA256.csv` gives hashes of the files uploaded to GitHub. Archives reduce the number of web-upload files without omitting scientific payload. They do not contain full production trajectories or complete raw molecular-input archives.


This deposit contains the current numerical source data and analysis code supporting five main figures and nineteen supplementary figures. It preserves the frozen scientific files byte for byte. The release also includes original laboratory workbooks/Prism records, laboratory report and images, representative case structures, the retained sixteen-residue input matrix, and existing strong/stress/merged reporting tables. No molecular-dynamics simulation, energy calculation, threshold optimization, new resampling or significance test was run to assemble this deposit.

## Start here

| Directory or file | Contents |
|---|---|
| `source_data/workbooks/` | Source Data 1–5 and Supplementary Tables 1–4: nine indexed, multi-sheet numerical workbooks. |
| `source_data/tables/` | Full-precision source CSV/JSON tables and numerical figure assets, including all candidate pairs and complete scans rather than selected favorable cells. |
| `source_data/originals/` | Project laboratory originals, accepted case PDB/SDF coordinates and scientific audit records. |
| `source_data/original_input_arrays/` | Existing N=143 × 16-residue NPZ and metadata, checked against the frozen wide CSV. |
| `source_data/additional_reporting/` | Previously completed separate-cohort and merged equal-budget reporting tables added symmetrically for manuscript reporting. |
| `source_data/provenance/` | Molecular input manifests, version/hash evidence and accepted per-case/per-residue ASGBIE exports. |
| `source_data/code/` | Retained plotting/workbook code and the exact audited ASGBIE implementation/configuration. |
| `figures/` | Current five main figures in original PDF and TIFF exports. |
| `supporting_information/figures/` | Current nineteen supplementary scientific figure PDFs, S01–S19. |
| `DATA_COVERAGE.csv` | Precisely what is included, what is indexed only, and the relevant paths. |
| `COPY_PROVENANCE_SHA256.csv` and archive/upload manifests | Source-copy verification and hashes of the actual archived/uploaded payload. |
| `CITATION_METADATA.json` | Current citation metadata; authors, DOI and reuse license are not invented. |

The public numbering is controlled by `source_data/DATA_CONTAINER_INDEX.csv`. Historical names such as `Figure4_S4` and `Table_S13` remain source-file identifiers. Historical provenance captions and old Word paragraph pointers are evidence snapshots, not an instruction to substitute older results. The manuscript and its current supplementary captions provide the scientific interpretation.

## Scientific scope

The corrected activity benchmark excludes the structure-to-experiment mismatch involving `1-7-6` and uses N=213. Structural/prediction registry records can still contain 214 entries. The sixteen-residue complete-case analysis uses N=143 and 70 active records. Missing residue contributions are not imputed as zero. The original pre-assay selection chronology is separate from refreshed post-assay energetic scores and exploratory gate/ranking comparisons. All equal-budget comparisons use global same-K selection, not source-matched quotas.

The laboratory screen has one confirmed well per compound at each of three concentrations (1, 10 and 50 µM). The report's preliminary positive/negative calls are preserved; they are not fitted IC50 values, independent replicates, or selectivity measurements. The retained ADP-Glo/Dual-GLO metadata disagreement and incomplete historical assay-condition records are preserved in the scientific source/audit tables. Historical S09C coverage includes the invalidated activity link and is retained as registry provenance only.

Accepted ASGBIE scientific exports cover 368 Boltz-start, 368 Docking-start and 11 crystal-start cases (747 total). The local exports contain the recorded per-case and per-residue results and source hashes. The original five retired pose-rescue roots and erroneous older MD trajectories are not publication inputs and are not included.

## Large original data: indexed, not uploaded here

**This repository does not contain the production trajectories or complete original prediction/docking-input archives.** `source_data/ORIGINAL_LARGE_DATA_POINTERS.csv` records their retained cluster/archive paths and historical hash evidence. These are provenance pointers, not public download links and not a fresh remote existence check. The corresponding accepted-input manifests and preservation receipts are included locally, but an archive pointer is not the archived bytes. No terabyte-scale data deposit or DOI is claimed.

`DATA_COVERAGE.csv` distinguishes deposited bytes from indexed-only material. Third-party journal PDFs, licensed Amber/force-field resources, model weights, credentials, unrelated libraries and internal author-query/editorial documents are excluded. Separate persistent hosting for original trajectories and archived molecular inputs remains necessary for a complete raw-trajectory data deposit.

## Code and reproduction

The ASGBIE code is a pinned implementation snapshot, not a turnkey portable simulator. See `source_data/code/ASGBIE_implementation/README.md` and its exact configuration/SHA provenance. It requires matching molecular inputs and trajectories, Amber/AmberTools resources and the documented Python dependencies. Site-specific source paths remain unchanged for provenance and must be mapped to a local authorized environment. No cluster submission, installer, cleanup transaction, GitHub workflow or deployment controller is supplied by this packaging step.

The separate panel sum and hotspot-total score have different definitions; `dIE_3S` denotes the 3σ fluctuation filter, not the 3 ns temporal windows. The frozen implementation and tables retain these definitions. Do not relabel the model-based residue perturbation scores as experimentally measured mutation free energies.

## Integrity, citation and reuse metadata

`QA.json` records copy preservation, array-to-table equality, sizes, symlink checks and a credential-pattern scan. `ARCHIVE_CONTENT_MANIFEST_SHA256.csv` and `UPLOAD_MANIFEST_SHA256.csv` contain SHA256 hashes of archive members and uploaded files. The check is an integrity and packaging audit, not a new scientific acceptance audit of remote simulations.

The manuscript authors/affiliations and persistent dataset identifier have not yet been supplied for citation metadata. No DOI, author list or reuse license has been invented. `CITATION_METADATA.json` is deliberately descriptive metadata rather than an invalid authorless CITATION.cff. A GitHub repository URL provides access but does not itself assign a DOI. Reuse/license metadata should be completed by the authors.
