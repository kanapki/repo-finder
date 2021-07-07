## Repo Finder
**An application for searching repositories in GitHub.** The searching results are shown in a paginated table.

### Screenshot
<p align="center">
  <img src="https://raw.githubusercontent.com/kanapki/repo-finder/master/screenshots/screenshot1.png" width="600">
</p>

### How it Works
##### Search by names
Users can search repositories by names. The application returns repositories with names containing the keyword.

##### Filter by languages
While searching, users can choose to filter repositories in certain languages. If no specific language is selected, the application searches for corresponding repositories in all languages.

##### Sort
Users can sort the results by name, language and number of stars, by clicking on the column names.

### References
- [@octokit/rest](https://octokit.github.io/rest.js/v18)
- [multiselect-react-dropdown](https://github.com/srigar/multiselect-react-dropdown)
- [react-data-table-component](https://github.com/jbetancur/react-data-table-component)