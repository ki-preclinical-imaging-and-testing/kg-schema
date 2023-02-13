# kg-schema
Knowledge graph schema design using Arrows.app


## Introduction

Arrows.app is a free, cloud-based tool developed by Neo4j to aid in design of schema for semantic graph databases. It is an intuitive tool meant to support domain experts to work with schemas firsthand. By domain experts, I mean experts with domain knowledge of their respective scientific or business areas, not database experts.

Here are three steps to get setup and working with Arrows.app:

1.  Sign in or [create a Google account](#Create-a-Google-account) for work*

2.  [Authorize Arrows.app](#Connect-Arrows.app-to-your-Google-account) to access your Google account

3. Take 5 minutes to [learn more about Arrows.app](#Getting-started-with-Arrows.app)

	*NOTE: Even if you already have a personal Gmail account, it may be useful to create a new one for work. Google allows you to create many accounts, and each comes with more storage space, inbox, and settings for apps across the Google Cloud Suite. If you use Google Chrome browser, you can add the account as profile for easy access later.

## Create a Google account

First, choose a username. I recommend the following format:

	<first_name>.<last_name>.mit@gmail.com

For me, this is [adam.patch.mit@gmail.com](mailto:adam.patch.mit@gmail.com). Using a name like this increases your chances of finding an unused login and may be easier to remember.

Now you can follow [Google's instructions for creating an account](https://support.google.com/accounts/answer/27441?hl=en).

## Connect Arrows.app to your Google account

Once you have signed into your Google account, go to [Arrows.app](https://arrows.app/)

When you arrive, you should see something like this

![1-arrows app-landing](https://user-images.githubusercontent.com/50635885/218544012-38f07ae1-a173-4bc2-8e44-669a57186e1d.PNG)

We need to ensure the text in the top center no longer defaults to "Save to Web Browser Storage". Instead, we can authorize a connection to Google Drive, by clicking the bright orange box in the top right that says `Save to Google Drive` and clicking `Authorize` after reviewing the popup window.

![2-arrows app-authorize](https://user-images.githubusercontent.com/50635885/218544011-1289852a-8d80-4863-92b6-efd06269758a.PNG)

Now, a final popup window will ask you to `Choose an account to continue to arrows.app`. Make sure you pick the correct account - this final window is controlled by Google, so it is safe to enter your password upon request. Additionally, Neo4j is the developer of Arrows.app, so we trust this developer.

![3-arrows-app-select-account](https://user-images.githubusercontent.com/50635885/218549834-4e026524-60ce-4238-9b37-7c7ec998a333.PNG)

Once complete, you should be able to load, save, and share Arrows.app schemas using Google Drive! 

If something goes wrong, please let me know! Otherwise, feel free to follow some additional instructions in the following section.

## Getting started with Arrows.app

Arrows.app is part of Neo4j's toolkit, so it is designed minimally with some especially useful features. For example, it can automatically generate code templates based on the diagrams we design together visually. I am very curious to hear feedback on use from the rest of you.

To get started, you can follow [Neo4j's 4-minute video tutorial](https://www.youtube.com/watch?v=ZHJ-BrKJ8A4)

Our current goal is to establish mind maps of important metadata entities and relationships that can help describe and contextualize each modality's data. In principle, we can store and relate details at any level of your processes, instrumentation, and scientific context.
