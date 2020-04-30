# A New Home for SentimentIt
==========================

Since Amazon’s Mechanical Turk updated their API in June 2019, we have
been trying to update SentimentIt to work smoothly with the new system.
We implemented substantial updates to our platform in advance of these
change, yet despite several rounds of revisions we continued to
encounter serious bugs related to synchronizing across the systems that
are a consequence of the new AMT architecture.

To better serve our users we are migrating SentimentIt’s functionality
to a new package, [labelR](https://github.com/RydenButler/labelR), which
bypasses SentimentIt’s servers to send pairwise comparisons directly to
Mechanical Turk using its API. The labelR package assists users in
formatting the necessary files for creating qualification tests and
pairwise comparison tasks, as well as it provides wrappers for sending
and downloading comparisons through the MTurk API. labelR will continue
to grow with detailed documentation and additional functionality that
builds on the foundations of SentimentIt’s data labeling method.

All researchers with in-progress work on the SentimentIt platform were
notified of this development in February and were given the opportunity
to collect their data stored on our servers ***by April 1, 2020***.

If you have questions or concerns about how the deprecation of
SentimentIt has impacted your research, you can post on our [Google
group](https://groups.google.com/forum/#!forum/SentimentItSupportGroup)
dedicated to supporting SentimentIt users who are making the transition
to labelR.

We apologize if these technical difficulties have interrupted your
research and hope that you found the SentimentIt platform useful while
it was in operation.

\- The SentimentIt Team

