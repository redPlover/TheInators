---
title: "Honzik's First Post"
date: 2024-09-12T11:03:20-04:00
author: 'Honzik'
---

## Hey Charlie
This is our page's **first post!** Wow, what an adventure. We're currently using [Hugo](https://gohugo.io) with the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme to run this *static* site. LMK if you want to migrate to something else though.

### Code Snippet
For the memories, here's a snippet of some robot code.
```java
private void intake() {
    if (!aimerAtIntakePosition()) {
        aimerIo.setAimAngleRad(ScoringConstants.intakeAngleToleranceRadians, true);
    }
    shooterIo.setKickerVolts(ScoringConstants.kickerIntakeVolts);

    if ((hasNote()) || action != ScoringAction.INTAKE) {
        state = ScoringState.IDLE;
    }
}
```

### Canada's Finest
Here's a picture of some Canadian geese. They love to take up sidewalk space and yell at freshmen. Their favorite times to be out are in between class change.
<!-- {{ $image := .Resources.Get "geese.jpg" }} -->
<!-- <img src="{{ $image.RelPermalink }}" width="{{ $image.Width }}" height="{{ $image.Height }}"> -->
![alt geese](geese.jpg)
