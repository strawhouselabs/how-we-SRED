# Documenting SR&ED in an agile world 
## How we SR&ED at Strawhouse

A portion of the projects we work on at Strawhouse are highly experimental and improve the state-of-the-art in our field. As such, we make use of the [Scientific Research and Experimental Development Tax Incentive](http://www.cra-arc.gc.ca/txcrdt/sred-rsde/menu-eng.html) program (SR&ED).

A big challenge of the SR&ED program is appropriately identifying and documenting the uncertainties which your business is working with. Identifying and documenting these uncertainties is required to make a claim. There's a wealth of software out there for tracking SR&ED projects, but we have found that it is a demanding use of time and comes with a significant cost.

## Quick Preamble

- Collect and store staff member task allocation and completion for the long haul. We use a Kanban board called Clubhouse for this. Tools such as Asana, Jira or Trello are appropriate too. This will be necessary to justify time spent on activities related to SR&ED.
- Use some form of source control. We use Git with Github. This will be evidence of the work completed by staff members allocated to SR&ED. It also acts as evidence of structured experimentation.
- Get "Daily Uncertainty Updates" from your team members to identify SR&EDable activity and justify projects.

## Strategy One - Daily Uncertainty Updates

First, we imparted some experience on the team with examples of what makes a good SR&EDable uncertainty and what does not. We also explain how significant the SR&ED program is for our success - the program is core to why research activity happens in Canada, and its value is hard to overstate. As some examples:

- Routine create-read-update-destroy applications are likely not SR&ED.
- Anything you already know how to do, are confident will work, or has been done in the past is not experimental.
- Structured experiments, testing methods to find a solution to a problem indicates something often SR&ED.
- e.g., a automated system for identifying some core variable to business could be experimental.
- e.g., testing different algorithms for performing some task in an adequate amount of time.

Then, we set up the service [IFTTT](http://ifttt.com/) to post once per day in our developer Slack channel asking the staff to each complete a "daily work uncertainty report." 

![IFTTT Configuration](https://d2ppvlu71ri8gs.cloudfront.net/items/1H0L081A2i0a1w222m2E/Screen%20Shot%202017-05-04%20at%204.31.56%20PM.png?v=14c02386)

The configuration and integration is simple and can be done by anyone. This post links off to a [Google Form](https://docs.google.com/forms/u/0/), which provides just two questions:
1. "What project did you work on today?" 
2. "Describe any experiments, difficulties or uncertainties you ran in to on that project." 

For context, the five conditions necessary for work to be SR&ED, are provided right alongside these questions.

1. Was there a scientific or a technological uncertainty?
2. Did the effort involve formulating hypotheses specifically aimed at reducing or eliminating that uncertainty?
3. Was the overall approach adopted consistent with a systematic investigation or search, including formulating and testing the hypotheses by means of experiment or analysis?
4. Was the overall approach undertaken for the purpose of achieving a scientific or a technological advancement?
5. Was a record of the hypotheses tested and the results kept as the work progressed?

This, Google Forms produces a spreadsheet of these results. A senior staff member with SR&ED experience reviews this regularly and adjusts the descriptions to be clear. Eventually, these answers are used to complete [Form T661](http://www.cra-arc.gc.ca/E/pbg/tf/t661/README.html), the primary SR&ED form. During tax season, this produces both an artefact of evidence (combined with Git logs, task assignment and other technical artefacts) as well as a valuable asset to timeline, describe and evaluate SR&EDable activity.

## Strategy Two - Blogging

A number of companies we've talked to about SR&ED have utilized the same strategy as strategy one, but on a public facing blog. An advantage to this method is that the authors are forced to structure their posts for the public.

In this case, we suggest still providing the context of the "5 conditions" proximate to the writing interface.

## Resources
- [SR&ED Claimants Guide](http://www.cra-arc.gc.ca/txcrdt/sred-rsde/clmng/clmngsrd-eng.html)
- [How to Document Uncertainty for SR&ED?](http://rdactionconsultant.com/en/2016/09/20/how-to-document-uncertainty/)
- [Form T661, the form you will use to document your project formally](http://www.cra-arc.gc.ca/E/pbg/tf/t661/README.html)
