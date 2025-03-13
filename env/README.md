# Environment

This contains environment specific configuration as separate directories.

NOTE: Separate values files are used for the image vs. environment specific configuration
so that git commits to the `values-image.yaml` can be ignored by the `config` Warehouse,
preventing unnecessary Freight to be generated for the `render-envs` Stage.
