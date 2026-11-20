# Johnny animated companion

Portable artwork package for importing a new custom pet into an account with compatible ChatGPT Work-mode Pets support. The original pet was named Jonathan Oh; this package defaults to Johnny.

## Install
1. Attach this ZIP to a conversation in an environment with custom Pets support.
2. Paste INSTALL-PROMPT.txt. The assistant should inspect this package and follow its current Pets instructions.
3. Review the motion preview. The assistant must validate the exact PNG, prepare an account-scoped upload, create a new pet, activate it, and confirm the active state.

The supported lifecycle in the available Pets interface is `validate_pet_spritesheet` -> `prepare_pet_upload` -> `create_pet` -> `select_pet`, with `list_pets` for verification. The returned upload session belongs to the importing account. A pet ID from another account is not an installer.

## Compatibility and limits
This is an asset package, not a standalone app, extension, executable, or universal one-click installer. It does not install a plugin or grant account access. It works only where custom animated Pets and the required import tools are available. A Codex, ChatGPT, or dot conversation alone does not guarantee that support. No manual filesystem destination or undocumented settings change is required or supplied. If your environment lacks the Pets feature/tools, stop and ask it to identify the supported setup route; this ZIP cannot add the feature.

The PNG is v2: 1536 x 2288 RGBA, an 8 x 11 grid with 192 x 208 cells. Rows 0-8 contain idle, right movement, left movement, waving, jumping, failed, waiting, active work, and review; rows 9-10 contain sixteen clockwise look directions. Unused cells are transparent. Do not resize, re-encode, crop, or tile this finished sheet before validation.

## Included files
- spritesheet.png: exact validated installation artwork.
- manifest.json: geometry, description, and SHA-256 integrity checksum.
- preview.gif / preview.mp4: labeled nine-state motion preview.
- preview-stills.png: four labeled representative frames.
- contact-sheet.png: all animation and look-direction frames.
- INSTALL-PROMPT.txt: copyable import request.

## Validation and privacy
The supplied PNG passed structural, animation-quality, and look-direction checks, plus the available Pets preflight, when exported on November 20, 2026. The recipient must run validation again in their own account; future compatibility is not guaranteed.

This package contains only the finished illustrated character, previews, and installation documentation. It excludes the photographic reference, private messages, original research, account identifiers, upload sessions, signed URLs, credentials, and local source paths. The character is a stylized likeness, not an official endorsement. No executable scripts are included.
