# cargo-clippy documentation verification

Approved scope: verify the GitHub full-analysis workflow in openlibing-test/ripgrep.
Use the documented Rust 1.98.1, clippy-sarif 0.8.0, and scan command first.
Use a dedicated validation branch, source_path '.', beta upload, and the organization
secret PRIVATE_ACTIONS_READ_TOKEN to check out the private uploader after scanning.
Pin uploader 05d5ea9e9f9a76497022ccab322f6dc22d827820; never persist credentials.
Retain logs, original and enriched SARIF, source-location audit, and callback evidence.
Document failures separately from any corrected verification run. No upstream PR.
