# ChanGen
Generate changelog from git tag/commit.

This could be useful if you use a linear semantic versioning/tagging scheme.

# Usage
Run in your terminal:

```
$ changen PATH_TO_YOUR_GIT_REPO
```

# Demo output
Running against [Semantic Versioning Specification](https://github.com/mojombo/semver) yields:

## v2.0.0 (2013-06-18)
- This is really the 2.0.0-rc.1 spec. 1.0.0 was previously released.
- Remove redundant rule 3. Closes #7.
- Wrap.
- Dash -> hyphen. Fixes #16.
- Dash -> hyphen. Fixes #16.
- Added link to IETF-hosted RFC 2119 spec.
- Replace the word "dash" with "hyphen".
- Replace the word "dash" with "hyphen".
- Fix typo
- Fix typo
- Make version format consistent
- Change sentence to remove inapplicable "Remember"
- Change sentence to remove inapplicable "Remember"
- Change "be comprised of" to "comprise"
- Change "be comprised of" to "comprise"
- Updated to RC2, with new definition for build metadata.
- Removed an extraneous slash
- Add description of build metadata
- Omit build metadata from precedence rules
- Removed the plus sign and added examples
- Fixed grammar mistake
- Add space between "hypen" and regex.
- Add space between "hypen" and regex.
- Fixes #40, adding a statement about the basis of semver. From @icylace.
- Fixes #12 with a new PR, updated to reflect pre-release and build metadata.
- Fixes #40, adding a statement about the basis of semver. From @icylace.
- Replaces #30. Updated wording as suggested
- updated as suggested
- added FAQ entry regarding semver version string size. Fixes #79.
- added FAQ entry regarding semver version string size. Fixes #79.
- Reword scenario of accidental breaking changes
- Remove the details for pre-release and build metadata from the summary
- Reword scenario of accidental breaking changes
- Cleaned up punctuation and format of summary
- Section 9: Clarify pre-release definition
- Section 11: A larger set of pre-release is higher
- Attempt to clarify precedence even more.
- Attempt to clarify precedence even more.
- Section 10: Clarify language around build metadata precedence
- Clarify non-empty build metadata
- Be more precise about version precedence
- Attempt to clarify precedence even more.
- Be more precise about version precedence
- Be more precise about version precedence
- No leading zeroes on numeric identifiers
- No leading zeroes on numeric identifiers
- by one -> SHOULD, not MUST
- removed increments by 1
- removed increments by 1

## v1.0.0-rc.1 (2011-11-25)
- Delimit pre-release versions by dash instead of dot.
- FAQ on bufixes returning functionality to documented public API.
- Add FAQ section on 0.y.z phase releases.
- Make patch/minor version resetting explicit.
- Remove SemVerTag sub-spec. It is a distraction.
- Version integers must be non-negative. Closes mojombo/semver.org#47.
- New school pre-release syntax and semantics.
- Add deprecation clarification. Closes mojombo/semver.org#24.
- Mark as rc~1.
- Use . instead of ~ as pre-release part separator.
- Correct build precedence example.
- Fully specify pre-release and build versions with arbitrary dot elements.
- Use new-style pre-release version rc.1 in header.

## v1.0.0-beta (2011-06-08)

## v1.0.0 (2011-09-06)
- Fix link to GitHub project.
- Delimit pre-release versions by dash instead of dot.
- FAQ on bufixes returning functionality to documented public API.
- Add FAQ section on 0.y.z phase releases.


# License

Copyright (c) 2015 Jingwei "John" Liu

Licensed under the MIT license.
