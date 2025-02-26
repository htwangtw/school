---
type: "modules" # DON'T TOUCH THIS ! :)

# Title of your project (we like creative title)
title: "fMRI Parcellation"

# Your project GitHub repository URL
github_repo:

# If you are working on a project that has website, indicate the full url including "https://" below or leave it empty.
website:

# List +- 4 keywords that best describe your project within []. Note that the project summary also involves a number of key words. Those are listed on top of the [github repository](https://github.com/PSY6983-2021/project_template), click `manage topics`.
# Please only lowercase letters
tags: [fmri, parcellation, atlas]

# Summarize your project in < ~75 words. This description will appear at the top of your page and on the list page with other projects..

summary: "The objectives of this module are to: 1) Understand the basis of the signal used in functional magnetic resonance imaging. 2) Know the main steps of preprocessing fMRI data. 
3) Know how functional connectivity is calculated, and how it is most commonly used. 4) Know the main brain parcellations and associated technical challenges
."

# If you want to add a cover image (listpage and image in the right), add it to your directory and indicate the name
# below with the extension.
image: "parcellation.png"
---
<!-- This is an html comment and this won't appear in the rendered page. You are now editing the "content" area, the core of your description. Everything that you can do in markdown is allowed below. We added a couple of comments to guide your through documenting your progress. -->

## Information

The estimated time to complete this training module is 1.5h.

The prerequisites to take this module are:
 * the [installation](/modules/installation) module.
 * the [python data analysis](/modules/python_data_analysis) module (recommended for Python familiarity).
 * the [fmri connectivity](/modules/fmri_connectivity) module 

Contact Desiree Lussier if you have questions on this module, or if you want to check that you completed successfully all the exercises.

## Resources
The first portion of this module was presented by Pierre Bellec during Brainhack School 2020 and teh notebook was created by Desiree Lussier for this module.

The tutorial slides are available [here](https://docs.google.com/presentation/d/1mTJoOSRKtGzhWeNLa9PXyKUYA0p9733UHVWrmIyi4zs/edit?usp=sharing).

The video presentation is available here:
<iframe width="560" height="315" src="https://www.youtube.com/embed/7uMVRebuDZo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Exercise

 * Watch the video presentation by Pierre Bellec and go over the slides.
 * Download the notebook created for this module found [here](https://github.com/BrainhackMTL/psy6983_2021/blob/master/content/en/modules/fmri_parcellation/atlas_parcellations.ipynb)
 * Run the notebook to view the parcellation for the atlas example.
 * Create new code blocks in your notebook and the example to retrive three other atlases using Nilearn datasets, the documentation for which you can find [here](https://nilearn.github.io/modules/reference.html#module-nilearn.datasets), and view the atlases in your notebook.
 * Answer the discussion at the bottom of the notebook in the markdown block provided and save.
 * Follow up with Désirée Lussier to and validate you completed the exercise.
 * 🎉 🎉 🎉 you completed this training module! 🎉 🎉 🎉

## More resources
You can watch my talk on dynamic parcellation (in French) [here](https://www.youtube.com/watch?v=5dA_ujGGtIY). If you are curious about how the embeddings of different parcellations compare you can check out my OHBM 2021 poster [here](https://drive.google.com/file/d/1O00bbKyI3Hqkah93iN83xpL10hMvygSt/view?usp=sharing) and check out Sebastian Urchs' paper on the MIST atlas [here](https://mniopenresearch.org/articles/1-3)
