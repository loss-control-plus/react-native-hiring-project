# Loss Control Plus
## React Native Hiring Project

<!-- vscode-markdown-toc -->
* 1. [React Native Developer](#ReactNativeWebDeveloper)
	* 1.1. [READ THIS BEFORE YOU BEGIN](#READTHISBEFOREYOUBEGIN)
	* 1.2. [Instructions](#Instructions)
	* 1.3. [Project Requirements](#ProjectRequirements)
		* 1.3.1. [Scenario](#Scenario)
		* 1.3.2. [Business Facts](#BusinessFacts)
		* 1.3.3. [Success Conditions](#SuccessConditions)
	* 1.4. [Guidelines](#Guidelines)

<!-- vscode-markdown-toc-config
	numbering=true
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->

##  1. <a name='ReactNativeWebDeveloper'></a>React Native Developer

###  1.1. <a name='READTHISBEFOREYOUBEGIN'></a>READ THIS BEFORE YOU BEGIN

This hiring project is intended to gauge a developer's ability to both work with the technologies we are using, as well as their soft-skills.

Technical prowess is a good thing but, by itself, is not enough to earn a spot on our team.

Do not squash or rebase your commits.

###  1.2. <a name='Instructions'></a>Instructions

1. Fork this repo.
2. Review the guidelines
3. Follow the Project Requirements.
4. Reach out with any questions.
5. Submit a pull request when your project is finished.

###  1.3. <a name='ProjectRequirements'></a>Project Requirements

####  1.3.1. <a name='Scenario'></a>Scenario

Welcome to Widgets Inc. We are the hottest app development company in the insuretech space. We would like to build a disruptive app that can be used to easily perform a home inspection.

...but there's a catch.

####  1.3.2. <a name='BusinessFacts'></a>Business Facts

- Some homes are in very rural areas where there is no reliable access to the internet. The app must work for performing an inspection without an internet connection.
- No data should be stored in "cache"
- No photos should be stored in the user's camera roll.

####  1.3.3. <a name='SuccessConditions'></a>Success Conditions

1. The questions should be programmatically generated from the questions.json file in this repo based upon the inspection type selected.
2. To sync, every inspection should be uploaded to an S3 bucket in a self-contained "directory". Questions + Answers should be in a JSON file and photos should be tied to answers via data entries in the JSON as well as naming convention.
3. The S3 credentials should be configurable so that the user can supply their own S3 bucket.
4. Offline data should survive a phone reboot, app crashes, and a manual clearing of the app cache by the user.
5. App should be performant and not slow down even if hundreds of questions are required for an inspection type.
6. The app needs to work on reasonably new iOS and Android phones + tablets.
7. All answers (and corresponding photos) must be able to be synced up to an S3 server after the inspector returns to a place where there is reliable internet access.
8. Add additional questions from the "Total Home Inspection" checklist pdf in the project repo to both inspection types. The Deluxe home inspection should contain all questions from the Basic Home Inspection but contain additional or more thorough data.

###  1.4. <a name='Guidelines'></a>Guidelines

1. Commit early, commit often. We would love to see more commits showing the process you took to get to the finished product. Do not squash or rebase your commits.
2. Please use eslint.
3. We'd prefer Typescript to JavaScript but it's not absolutely required.
4. Writing tests would be a massive point in your favor.
5. Spend as much, or as little, time on this as you wish. That said, we'd prefer a project be delivered within 72 hours of acceptance.
6. We encourage you to reach out to us with any questions you may have. Doing so will not be seen as detrimental to your delivered project.