# Intentdefinition-diff

This tool solves a common Xcode localization problem: when you modify an intentdefinition file, Xcode doesn't update existing translations. Normally, you'd need to delete and recreate all localization files from scratch. This tool makes the process easier by comparing your original and modified files, showing exactly what changed.

## 🔗 [Live Demo](https://kashmiry.github.io/Intentdefinition-diff/)

## Purpose

When working with SiriKit intents in Xcode:
- Modifying the original intentdefinition file doesn't update existing localization files with new changes
- Every time you make changes to intentdefinition, you would normally have to remove and re-add a localization
- This tool identifies exactly what strings changed between versions
- You can then selectively update just the necessary translations without rebuilding everything
  
## How to Use

1. Paste your original intentdefinition strings in the left textarea
2. Paste your new/updated intentdefinition strings in the right textarea
3. Click "Compare" to analyze the differences
4. View missing and added strings in the results section
5. Use the copy button to extract just the differences for easy updating

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
