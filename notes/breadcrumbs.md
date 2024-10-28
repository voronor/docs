# Documentation Breadcrumbs Script

Quick guide on using our breadcrumbs automation script for the OP Stack documentation.

## What the Script Does

*   Creates `.mdx` files for each folder (breadcrumb pages)
*   Populates Card components linking to contained files
*   Preserves existing descriptions that already
*   Maintains consistent navigation structure

## Using the Script

Breadcrumbs for the docs can be generated by running:

```bash
pnpm create-breadcrumbs
```

### What to Watch For

1. **Before Running**
   *   Commit your current changes
   *   Ensure you're in the docs root directory
   *   Target folders should exist: `builders`, `chain`, `stack`, `connect`

2. **After Running**
   *   Review generated `.mdx` files in each folder
   *   Check updated descriptions
   *   Verify Card components and links

## Common Issues

*   ***Script fails**: Ensure you're in the root directory
*   **No files generated**: Check folder structure matches expected paths
*   **Unexpected content**: Review git diff before committing