<div align="center">
  <br>
  <img alt="Open Sauced" src="https://github.com/open-sauced/assets/blob/main/logos/logo-on-dark.png">
  <h1>🍕 Pizza Lovers Repository 🍕</h1>
  <strong>Welcome to OpenSauced's Pizza Lovers Repository!</strong>
</div>
<br>

# Pizza Lovers Repository

## Introduction

The Pizza Lovers Repository is a collaborative project where we can come together and contribute pizza-related content. Whether you have a fantastic pizza recipe, an interesting pizza fact, or just want to share your opinions on the best pizza toppings, this repository is the perfect place to do it!

## Repository Structure

### [Pizza Recipes](pizza-recipes.md)

Share your favorite pizza recipes. Whether it's a classic Margherita pizza or a unique creation of your own, this category aims to provide a variety of pizza recipes for everyone to enjoy. Contributors can share their recipes, including ingredients, cooking instructions, and other relevant details. Feel free to include images of your pizza creations to inspire others to try your recipes!

### [Pizza Facts and Trivia](pizza-facts-&-trivia.md)

Share your interesting and informative pizza-related facts. Contributors can provide verified and accurate information about the history of pizza, trivia about different pizza styles, nutritional aspects, or any other factual details that enhance our understanding and appreciation of pizza. Whether it's uncovering the origins of a specific pizza topping or revealing fascinating facts about renowned pizzerias, this category aims to enlighten and educate pizza enthusiasts.

### [Regional Pizza](regional-pizza.md)

Share interesting and informative pizza-related facts about your hometown or country. You can provide verified and accurate information about its history of pizza, trivia about different pizza styles, nutritional aspects, or any other factual details that enhance our understanding and appreciation of pizza. Whether it's uncovering the origins of a specific pizza style, topping, or revealing fascinating facts about renowned pizzerias, this category aims to enlighten and educate pizza enthusiasts.

## How to Contribute

---

**We only receive one added item per file and one PR for each open issue ([#32](https://github.com/open-sauced/pizza-verse/issues/32), [#35](https://github.com/open-sauced/pizza-verse/issues/35), and [#36](https://github.com/open-sauced/pizza-verse/issues/36)) per contributor**.

So, you may add only one pizza recipe, one fact or trivia, and one regional pizza in separate PR based on the issue. If you want to add more than one, please open an issue and explain why we should add it.

---

Follow the steps below to get started:

1. [Fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo#forking-a-repository) this repository to your own GitHub account.
2. [Clone](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository#cloning-a-repository) the forked repository to your local machine.
3. [Create a new branch](https://www.shellhacks.com/git-create-new-branch-and-checkout/) with a name related to your contribution, for example, `feature/add-pizza-recipe`.
4. You can now add a new pizza fact or trivia to the [`pizza-facts-&-trivia.md`](https://github.com/open-sauced/pizza-verse/blob/main/pizza-facts-%26-trivia.md), a new style of pizza to the [`regional-pizza.md`](https://github.com/open-sauced/pizza-verse/blob/main/regional-pizza.md), or a new recipe to the [`pizza-recipes.md`](https://github.com/open-sauced/pizza-verse/blob/main/pizza-recipes.md) file. Remember, you may only submit **one** new item in a file.
5. Follow our [`style-guide.md`](https://github.com/open-sauced/pizza-verse/blob/main/style-guide.md) to format your content.
6. Once you're done, [add](https://github.com/git-guides/git-add#common-usages-and-options-for-git-add) and [commit](https://github.com/git-guides/git-commit#common-usages-and-options-for-git-commit) your changes, then [push](https://github.com/git-guides/git-push#common-usages-and-options-for-git-push) them to your forked repository.
7. Submit a [pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request#creating-the-pull-request) to have your contribution reviewed and considered for merging into the main repository.
8. Engage with other contributors and maintainers through comments and discussions.

## Keeping Branch Up to Date and Resolving Merge Conflicts

Merge conflicts occur when there are changes on the same line(s) in the same file(s) from two different branches. Since the main purpose in this repository is to add a new item to the `pizza-facts-&-trivia.md`, `pizza-recipes.md`, and `regional-pizza.md` files, there is a chance that you will encounter and need to resolve conflicts because maintainers might have merged PRs before yours while you're working on your changes or waiting for your PR to be reviewed.

In this section, we will walk you through how to keep your branch up to date and how to resolve conflicts.

### Keeping Branch Up to Date

Before resolving conflicts, your branch has to be in sync with the latest changes in the `main` branch of the original (`upstream`) repository.

First, you must update your forked (`origin`) repository:

1. Go to your forked repository on GitHub.
2. Click the "Sync fork" button.
3. Click the green "Update branch" button.

Then, pull the latest changes in the `main` branch in the `origin` repository to your local working branch by following these steps in your terminal:

1. Go to your working branch.

   ```bash
   git checkout <your-branch-name>
   ```

2. Pull the latest changes with this command:

   ```bash
   git pull origin main
   ```

### Resolving Merge Conflicts

First, you need to pay attention to the conflicts. On which line(s) does the conflict happen? What are the differences?

Everything between the `<<<<<<< HEAD` and `=======` is the changes that you worked on (current changes). And everything between the `=======` to `>>>>>>>` is the incoming changes from the remote `main` branch that you have pulled.

Now, you must decide how you want to resolve the conflicts. Because the contributions in this repository are to add new items, you want to keep both yours and the incoming changes, which are the items from previous contributor(s).

Follow these steps to resolve the merge conflicts in this repository:

1. Click the "Accept Both Change" option on the top of your workspace in VSCode. If you haven't enabled this feature, check out [this article by Lee Stanton](https://www.alphr.com/vs-code-open-merge-editor/) to help you.
2. Fix anything necessary, such as duplicate sentences, etc. **Tips**: If you're confused, look at the markdown file in this repository to compare the current state of the content with your local file when fixing.
3. Move your item to the end of the list.
4. Add and commit your changes.

   ```bash
   git commit -am "Resolve merge conflicts"
   ```

5. Push your commits to your remote branch.

   ```bash
   git push
   ```

## Contribution Guidelines

All contributors are required to abide by our [Code of Conduct](https://github.com/open-sauced/.github/blob/main/CODE_OF_CONDUCT.md).

<img align="right" src="https://i.ibb.co/CJfW18H/ship.gif" width="200"/>To ensure a smooth and enjoyable experience for everyone, please adhere to the following guidelines when contributing to the Pizza Lovers Repository:

- Keep the content **relevant** to pizza. We love all things pizza-related!
- Ensure your content is **family-friendly** and suitable for all audiences.
- Provide **credible sources** for any facts or information you include.
- Respect the **[code of conduct](https://github.com/open-sauced/.github/blob/main/CODE_OF_CONDUCT.md)** and be kind and inclusive to others.
- Please check out the [Contributing guide](https://docs.opensauced.pizza/contributing/introduction-to-contributing/) for guidelines about how to proceed.
- We have a commit utility called [@open-sauced/conventional-commit](https://github.com/open-sauced/conventional-commit) that helps you write your commits in a way that is easy to understand and process by others.
- Feel free to comment on and discuss other people's contributions, but keep the discussions **constructive** and respectful.

We encourage you to experiment, learn, and have fun while contributing to the Pizza Lovers Repository! Let's celebrate the joy of pizza together. 🎉

## 🍕 Community

- Got Questions? Join the conversation in our [Discord](https://discord.gg/U2peSNf23P).
- Find OpenSauced videos and release overviews on our [YouTube Channel](https://www.youtube.com/channel/UCklWxKrTti61ZCROE1e5-MQ).

## ⚖️ LICENSE

MIT © [OpenSauced](LICENSE)
