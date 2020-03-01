# Review my pull request

A GitHub repository that serves the purpose of learning how use GitHub's code review feature for pull requests.

# Usage

1. **Import** this repository to obtain a copy of it for yourself (do not fork it).

2. Create a remote branch named `pr` (this will use GitHub Actions to create a pull request for you to review in this repository).

3. Click on the Pull Requests tab of your copy of the repository, click on the pull request titled "Report most accomplished pilots", and then click on "Files Changed". Next click on the `star-wars.Rmd` file. Review the file and observe the following problems with the R Markdown report that was submitted via the pull request:
- Reasoning of the sentence on line 15
- Incompatibility with the sentence on line 15 with the code in the code chunk named `table-of-most-accomplished-pilots`
- Incorrect code in code chunk named `table-of-most-accomplished-pilots` (grouping by `film` instead of `starships`) leads to naming the wrong pilot as the most accomplished pilot on line 27
- Incorrect code in code chunk named `table-of-most-accomplished-pilots` (grouping by `film` instead of `starships`) leads to the use of the wrong character's picture in the image that is sourced in the code chunk named `top-pilot` (it should be a picture of Han Solo).

4. Add comments and suggested changes using the `+` sign beside the line numbers (the first time you do this will trigger the start of your code review. Need help? See [GitHub's how to on reviewing proposed changes in a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/reviewing-proposed-changes-in-a-pull-request).

5. After you have made all the comments and suggested changes, then add a general comment for the code review, select "Request Changes" and submit your code review.

6. Practice accepting code changes that you provided as suggestions by revisiting the Pull Requests tab of your copy of the repository and clicking on the pull request titled "Report most accomplished pilots". Scroll through the pull request comments and find the code suggestions. Then click on the "Commit suggestion button" for each suggestion. 

7. Click on the `...` beside the note that a request for changes was requested. Then click "Approve changes".

8. Finally click on the green buttons ("Merge Pull Request" & "Confirm merge") to merge the pull request.
