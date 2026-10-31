# Interactive HTML Tool Prompt Generator

Help session participants define their functional requirements, inputs with strict validations, and desired outputs to generate production-ready HTML single-file tools.

## 🚀 Live Demo on GitHub Pages
This repository is configured to open directly in your browser without any external dependencies.

### How to Run Locally
1. Download or clone this repository.
2. Double click `html_tool.html` or `index.html`.
3. The tool runs 100% offline with zero dependencies.

### Inputs Defined (4):
1. **Session Participant Name** (text) - Validation: `required`
2. **Tool Objective & Target Outcome** (textarea) - Validation: `min_length`
3. **Input Data Specification File** (text_file) - Validation: `file_extension`
4. **Target Processing Complexity Level** (select) - Validation: `required`

### Outputs Defined (3):
1. **Consolidated AI Master Prompt** (code_block) - Action: `copy_clipboard_button`
2. **Structured Technical Specification Table** (data_table) - Action: `on_screen_card`
3. **Exportable Requirement Document** (downloadable_file) - Action: `file_download_button`
