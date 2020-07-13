# Automatic Repair Tool


Based on our catalogue of build conflicts, we developed a prototype tool for repairing some kinds of Build Conflicts. The current implementation can repair build conflicts caused by <i>Unavailable Symbol</i>, <i>Unimplemented Method</i>, and <i>Duplicated Declaration</i>.

For that, once the tool verifies the occurrence of a build conflict, it uses our scripts (used to perform our study) to classify the conflict. In case the conflict was caused by one of the causes already supported, the tool further a solution. After that, the fix is presented to the developer, and in case he/she accepts the recommendation, a new commit is created and the necessary changes are applied.

For future work, we plan to evolve this prototype to cover the remaining build conflict causes of our catalogue. The prototype in available on <a href="https://github.com/leusonmario/FixMerge" target="_blank" > GitHub</a>. On this page, you can also find information and additional instructions for using the tool.

In case of any problems or questions, please contact us.