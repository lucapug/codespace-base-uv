# codespace_base_uv

Repository base per avviare un **Codespace** con `uv` già installato.

## Note

- Questo repo utilizza un file `.devcontainer/devcontainer.json` minimale che:
  - parte dall’immagine base `ubuntu`;
  - esegue l’installazione di **uv** (`curl -LsSf https://astral.sh/uv/install.sh | sh`) al momento della creazione del Codespace;
  - include l’estensione Python di VS Code per comodità.

In questo modo, ogni Codespace creato da questo repo ha già `uv` pronto all’uso.