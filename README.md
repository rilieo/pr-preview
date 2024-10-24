# PR Preview Testing

Planning on integrating with HackNYU repos b/c looking at CSS code is disgusting

## Notes
- Preview seems to only regenerate if `App.jsx` is modified. 
  - Doesn't regenerate if workflow file `preview.yaml` is changed; create a new pr to generate another preview.

- Labeling only runs workflow file on `main` b/c of the event `pull_request_target`
