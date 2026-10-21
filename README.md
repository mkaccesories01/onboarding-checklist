# onboarding-checklist

This module holds the first-run onboarding experience for the mobile app. After a few rounds of exploration, design approved a **3-step checklist pattern** on October 22. A new user sees three short, concrete tasks instead of a carousel of welcome screens. Each finished step is checked off right away, and the checklist steps aside once all three are done.

We picked a checklist over a tutorial because it gets people doing real things in the product right away, which lines up with our day-7 retention target of 40%. Every step is skippable, and progress is saved locally, so someone who leaves halfway through comes back to where they stopped.

## Structure

The flow ships as a Swift package that [`mobile-app-ios`](https://github.com/mkaccesories01/mobile-app-ios) imports. Step definitions live in a single config file, so product and design can reorder or reword steps without touching view code. All copy goes through the same review process as [`help-center-content`](https://github.com/mkaccesories01/help-center-content).

## Status

The flow is in progress and needs to be feature-complete before the November 1 freeze. Open items are tracked as issues here. Before opening a pull request for a visual change, please check the latest Figma file and actually read it, not just skim it.
