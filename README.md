# vAIst Builds

Public build runners for vAIst VST3 plugin compilation.

This repository is kept public to leverage unlimited GitHub Actions minutes for cross-platform VST3 builds.

## Workflow

The `faust-vst3.yml` workflow:
- Receives FAUST DSP code via `workflow_dispatch`
- Compiles to VST3 for macOS and Windows
- Uploads artifacts to R2 storage

## Related

Main application: [vst-generator](https://github.com/mottysisam/vst-generator) (private)
