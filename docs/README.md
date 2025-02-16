# Template

[![Project Status: Maintained][status-badge]][root] [![Repository Size][repository-size-badge]][root]

This repository serves as a general-purpose template for generating new projects.

## Credit

See [CREDIT.md][credit].

## Usage

### Creating a New Project Using This Template

#### GitHub (Recommended)

- Click on the green "Use this template" button at the top right of this page.
- Click on "Create a new repository".
- Fill in the repository name in the form that you see.
- Fill in the description in the form that you see.
- Select which visibility the project should have.
- Click on "Create repository".
- Fill in any extra information that you may need.
- Clone your new repository using `git clone`.

#### Manual

- Download the files of this repository, either via a zip archive, or using `git clone`.
- If you used `git clone`, delete the `.git` folder.
- If you are using version control (recommended), create the first revision after following the [checklist](#checklist).

### Checklist

The following serves as a checklist - a list of tasks to complete when creating a new project using this template.

- [ ] Update all files in the [`template/`][template] directory with your own information.
- [ ] If you are using a different system to track features, ideas, and/or issues, delete those files respectively.
- [ ] Move the following files from [`docs/`][docs] to [`template/`][template]:
  - [SECURITY.md][security].
  - [CODE_OF_CONDUCT.md][conduct].
- [ ] Commit your changes to version control if applicable.

## License

[Template][root] &copy; 2024-2025 [Esoteric Enderman][website] is licensed under the [AGPL 3.0][license].

## Topics

template templates template-project template-repository template-generic-repo

<!-- Link aliases -->

[root]: ../

<!-- Badges -->

[status-badge]: assets/images/badges/status/maintained.svg
[repository-size-badge]: https://img.shields.io/github/repo-size/esoterictemplates/template?style=for-the-badge&logo=git&label=Repository%20size

<!-- Files -->

[info]: ./README.md

[contact]: ./CONTACT.md

[license]: ../LICENSE

[template]: ../template
[docs]: ../docs

[features]: ../template/docs/FEATURES.md
[changelog]: CHANGELOG.md
[ideas]: TODO.md
[issues]: ISSUES.md

[citation]: ../CITATION.cff
[credit]: ../template/docs/CREDIT.md

[conduct]: ../template/docs/CODE_OF_CONDUCT.md

[security]: ../template/docs/SECURITY.md

<!-- IDE files -->

[idea-name]: ../.idea/.name

<!-- Links -->

[website]: https://enderman.dev

[free-software-foundation]: https://www.fsf.org/
[licenses]: https://www.gnu.org/licenses/
