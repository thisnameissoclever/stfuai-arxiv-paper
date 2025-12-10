# STFUAI Podcasts: Evaluation Corpus

## Overview

This document contains ground-truth evaluation data for 20 podcast episodes across 4 popular podcasts from 3 categories. Each episode was processed using STFUAI's semantic role-based speaker diarization system, and the results were manually verified against the actual episode content.

### Podcasts Evaluated

| Category  | Podcast                           | Episodes |
| --------- | --------------------------------- | -------- |
| News      | The Daily (NYT)                   | 5        |
| News      | Up First (NPR)                    | 5        |
| Narrative | The Way I Heard It with Mike Rowe | 5        |
| Self-Help | Happier with Gretchen Rubin       | 5        |

### Advertisement Definition

For evaluation purposes, an **advertisement** is defined as:

> A segment that (a) interrupts or is separate from the episode's primary editorial content, and (b) promotes a product, service, or brand - whether from a third-party sponsor or the podcast's own network/platform - in exchange for compensation or as part of a sponsorship arrangement.

**Included:**

- Third-party sponsor spots (dynamic or baked-in)
- Host-read ads for sponsors
- Pre-roll, mid-roll, post-roll ad breaks
- Network cross-promos that are clearly ad inventory

**Excluded:**

- "Rate and subscribe" calls-to-action
- Patreon/membership plugs
- Promo code mentions within editorial content
- "This episode was supported by listeners like you" funding acknowledgments
- Episode intros/outros that are just branding (theme music, title cards)
- Hosts mentioning products organically in editorial content

---

## Aggregate Results

*Complete this section after all episodes are evaluated.*

### Summary Statistics

| Podcast | Episodes | Total Ads | Detected | Missed | False Positives | Precision | Recall | F1 |
|---------|----------|-----------|----------|--------|-----------------|-----------|--------|-----|
| The Daily | 5 | | | | | | | |
| Up First | 5 | | | | | | | |
| Stuff You Should Know | 5 | | | | | | | |
| Happier | 5 | | | | | | | |
| **TOTAL** | **20** | | | | | | | |

### By Ad Type

| Ad Type | Total | Detected | Missed | Recall |
|---------|-------|----------|--------|--------|
| Dynamic pre-roll | | | | |
| Dynamic mid-roll | | | | |
| Dynamic post-roll | | | | |
| Host-read (baked-in) | | | | |
| Network cross-promo | | | | |

---

# THE DAILY (NYT)

---

## Episode 1: The Daily - [Title]

### Episode Metadata

- **Podcast:** The Daily
- **Episode Title:** 
- **Episode Date:** 
- **Total Duration:** 
- **RSS/Source URL:** 

### Detected Advertisements (System Output)

| # | Start Time | End Time | Duration | Speaker Role | Confidence | Notes |
|---|------------|----------|----------|--------------|------------|-------|
| 1 |            |          |          |              |            |       |
| 2 |            |          |          |              |            |       |
| 3 |            |          |          |              |            |       |
| 4 |            |          |          |              |            |       |
| 5 |            |          |          |              |            |       |

**Total detected ad time:** 

### Actual Advertisements (Ground Truth)

| # | Start Time | End Time | Duration | Ad Type | Sponsor/Product | Detected? |
|---|------------|----------|----------|---------|-----------------|-----------|
| 1 |            |          |          |         |                 |           |
| 2 |            |          |          |         |                 |           |
| 3 |            |          |          |         |                 |           |
| 4 |            |          |          |         |                 |           |
| 5 |            |          |          |         |                 |           |

**Total actual ad time:** 

### Missed Advertisements (False Negatives)

| # | Start Time | End Time | Duration | Ad Type | Why Missed? |
|---|------------|----------|----------|---------|-------------|
| 1 |            |          |          |         |             |

### False Positives (Incorrectly Flagged)

| # | Start Time | End Time | Duration | What It Actually Was |
|---|------------|----------|----------|----------------------|
| 1 |            |          |          |                      |

### Episode Metrics

- **True Positives (TP):** 
- **False Positives (FP):** 
- **False Negatives (FN):** 
- **Precision:** TP / (TP + FP) = 
- **Recall:** TP / (TP + FN) = 
- **F1 Score:** 2 × (P × R) / (P + R) = 

### Notes / Observations


---

## Episode 2: The Daily - [Title]

### Episode Metadata

- **Podcast:** The Daily
- **Episode Title:** 
- **Episode Date:** 
- **Total Duration:** 
- **RSS/Source URL:** 

### Detected Advertisements (System Output)

| # | Start Time | End Time | Duration | Speaker Role | Confidence | Notes |
|---|------------|----------|----------|--------------|------------|-------|
| 1 |            |          |          |              |            |       |
| 2 |            |          |          |              |            |       |
| 3 |            |          |          |              |            |       |
| 4 |            |          |          |              |            |       |
| 5 |            |          |          |              |            |       |

**Total detected ad time:** 

### Actual Advertisements (Ground Truth)

| # | Start Time | End Time | Duration | Ad Type | Sponsor/Product | Detected? |
|---|------------|----------|----------|---------|-----------------|-----------|
| 1 |            |          |          |         |                 |           |
| 2 |            |          |          |         |                 |           |
| 3 |            |          |          |         |                 |           |
| 4 |            |          |          |         |                 |           |
| 5 |            |          |          |         |                 |           |

**Total actual ad time:** 

### Missed Advertisements (False Negatives)

| # | Start Time | End Time | Duration | Ad Type | Why Missed? |
|---|------------|----------|----------|---------|-------------|
| 1 |            |          |          |         |             |

### False Positives (Incorrectly Flagged)

| # | Start Time | End Time | Duration | What It Actually Was |
|---|------------|----------|----------|----------------------|
| 1 |            |          |          |                      |

### Episode Metrics

- **True Positives (TP):** 
- **False Positives (FP):** 
- **False Negatives (FN):** 
- **Precision:** TP / (TP + FP) = 
- **Recall:** TP / (TP + FN) = 
- **F1 Score:** 2 × (P × R) / (P + R) = 

### Notes / Observations


---

## Episode 3: The Daily - [Title]

### Episode Metadata

- **Podcast:** The Daily
- **Episode Title:** 
- **Episode Date:** 
- **Total Duration:** 
- **RSS/Source URL:** 

### Detected Advertisements (System Output)

| # | Start Time | End Time | Duration | Speaker Role | Confidence | Notes |
|---|------------|----------|----------|--------------|------------|-------|
| 1 |            |          |          |              |            |       |
| 2 |            |          |          |              |            |       |
| 3 |            |          |          |              |            |       |
| 4 |            |          |          |              |            |       |
| 5 |            |          |          |              |            |       |

**Total detected ad time:** 

### Actual Advertisements (Ground Truth)

| # | Start Time | End Time | Duration | Ad Type | Sponsor/Product | Detected? |
|---|------------|----------|----------|---------|-----------------|-----------|
| 1 |            |          |          |         |                 |           |
| 2 |            |          |          |         |                 |           |
| 3 |            |          |          |         |                 |           |
| 4 |            |          |          |         |                 |           |
| 5 |            |          |          |         |                 |           |

**Total actual ad time:** 

### Missed Advertisements (False Negatives)

| # | Start Time | End Time | Duration | Ad Type | Why Missed? |
|---|------------|----------|----------|---------|-------------|
| 1 |            |          |          |         |             |

### False Positives (Incorrectly Flagged)

| # | Start Time | End Time | Duration | What It Actually Was |
|---|------------|----------|----------|----------------------|
| 1 |            |          |          |                      |

### Episode Metrics

- **True Positives (TP):** 
- **False Positives (FP):** 
- **False Negatives (FN):** 
- **Precision:** TP / (TP + FP) = 
- **Recall:** TP / (TP + FN) = 
- **F1 Score:** 2 × (P × R) / (P + R) = 

### Notes / Observations


---

## Episode 4: The Daily - [Title]

### Episode Metadata

- **Podcast:** The Daily
- **Episode Title:** 
- **Episode Date:** 
- **Total Duration:** 
- **RSS/Source URL:** 

### Detected Advertisements (System Output)

| # | Start Time | End Time | Duration | Speaker Role | Confidence | Notes |
|---|------------|----------|----------|--------------|------------|-------|
| 1 |            |          |          |              |            |       |
| 2 |            |          |          |              |            |       |
| 3 |            |          |          |              |            |       |
| 4 |            |          |          |              |            |       |
| 5 |            |          |          |              |            |       |

**Total detected ad time:** 

### Actual Advertisements (Ground Truth)

| # | Start Time | End Time | Duration | Ad Type | Sponsor/Product | Detected? |
|---|------------|----------|----------|---------|-----------------|-----------|
| 1 |            |          |          |         |                 |           |
| 2 |            |          |          |         |                 |           |
| 3 |            |          |          |         |                 |           |
| 4 |            |          |          |         |                 |           |
| 5 |            |          |          |         |                 |           |

**Total actual ad time:** 

### Missed Advertisements (False Negatives)

| # | Start Time | End Time | Duration | Ad Type | Why Missed? |
|---|------------|----------|----------|---------|-------------|
| 1 |            |          |          |         |             |

### False Positives (Incorrectly Flagged)

| # | Start Time | End Time | Duration | What It Actually Was |
|---|------------|----------|----------|----------------------|
| 1 |            |          |          |                      |

### Episode Metrics

- **True Positives (TP):** 
- **False Positives (FP):** 
- **False Negatives (FN):** 
- **Precision:** TP / (TP + FP) = 
- **Recall:** TP / (TP + FN) = 
- **F1 Score:** 2 × (P × R) / (P + R) = 

### Notes / Observations


---

## Episode 5: The Daily - [Title]

### Episode Metadata

- **Podcast:** The Daily
- **Episode Title:** 
- **Episode Date:** 
- **Total Duration:** 
- **RSS/Source URL:** 

### Detected Advertisements (System Output)

| # | Start Time | End Time | Duration | Speaker Role | Confidence | Notes |
|---|------------|----------|----------|--------------|------------|-------|
| 1 |            |          |          |              |            |       |
| 2 |            |          |          |              |            |       |
| 3 |            |          |          |              |            |       |
| 4 |            |          |          |              |            |       |
| 5 |            |          |          |              |            |       |

**Total detected ad time:** 

### Actual Advertisements (Ground Truth)

| # | Start Time | End Time | Duration | Ad Type | Sponsor/Product | Detected? |
|---|------------|----------|----------|---------|-----------------|-----------|
| 1 |            |          |          |         |                 |           |
| 2 |            |          |          |         |                 |           |
| 3 |            |          |          |         |                 |           |
| 4 |            |          |          |         |                 |           |
| 5 |            |          |          |         |                 |           |

**Total actual ad time:** 

### Missed Advertisements (False Negatives)

| # | Start Time | End Time | Duration | Ad Type | Why Missed? |
|---|------------|----------|----------|---------|-------------|
| 1 |            |          |          |         |             |

### False Positives (Incorrectly Flagged)

| # | Start Time | End Time | Duration | What It Actually Was |
|---|------------|----------|----------|----------------------|
| 1 |            |          |          |                      |

### Episode Metrics

- **True Positives (TP):** 
- **False Positives (FP):** 
- **False Negatives (FN):** 
- **Precision:** TP / (TP + FP) = 
- **Recall:** TP / (TP + FN) = 
- **F1 Score:** 2 × (P × R) / (P + R) = 

### Notes / Observations


---

# UP FIRST (NPR)

---

## Episode 6: Up First - [Title]

### Episode Metadata

- **Podcast:** Up First
- **Episode Title:** 
- **Episode Date:** 
- **Total Duration:** 
- **RSS/Source URL:** 

### Detected Advertisements (System Output)

| # | Start Time | End Time | Duration | Speaker Role | Confidence | Notes |
|---|------------|----------|----------|--------------|------------|-------|
| 1 |            |          |          |              |            |       |
| 2 |            |          |          |              |            |       |
| 3 |            |          |          |              |            |       |
| 4 |            |          |          |              |            |       |
| 5 |            |          |          |              |            |       |

**Total detected ad time:** 

### Actual Advertisements (Ground Truth)

| # | Start Time | End Time | Duration | Ad Type | Sponsor/Product | Detected? |
|---|------------|----------|----------|---------|-----------------|-----------|
| 1 |            |          |          |         |                 |           |
| 2 |            |          |          |         |                 |           |
| 3 |            |          |          |         |                 |           |
| 4 |            |          |          |         |                 |           |
| 5 |            |          |          |         |                 |           |

**Total actual ad time:** 

### Missed Advertisements (False Negatives)

| # | Start Time | End Time | Duration | Ad Type | Why Missed? |
|---|------------|----------|----------|---------|-------------|
| 1 |            |          |          |         |             |

### False Positives (Incorrectly Flagged)

| # | Start Time | End Time | Duration | What It Actually Was |
|---|------------|----------|----------|----------------------|
| 1 |            |          |          |                      |

### Episode Metrics

- **True Positives (TP):** 
- **False Positives (FP):** 
- **False Negatives (FN):** 
- **Precision:** TP / (TP + FP) = 
- **Recall:** TP / (TP + FN) = 
- **F1 Score:** 2 × (P × R) / (P + R) = 

### Notes / Observations


---

## Episode 7: Up First - [Title]

### Episode Metadata

- **Podcast:** Up First
- **Episode Title:** 
- **Episode Date:** 
- **Total Duration:** 
- **RSS/Source URL:** 

### Detected Advertisements (System Output)

| # | Start Time | End Time | Duration | Speaker Role | Confidence | Notes |
|---|------------|----------|----------|--------------|------------|-------|
| 1 |            |          |          |              |            |       |
| 2 |            |          |          |              |            |       |
| 3 |            |          |          |              |            |       |
| 4 |            |          |          |              |            |       |
| 5 |            |          |          |              |            |       |

**Total detected ad time:** 

### Actual Advertisements (Ground Truth)

| # | Start Time | End Time | Duration | Ad Type | Sponsor/Product | Detected? |
|---|------------|----------|----------|---------|-----------------|-----------|
| 1 |            |          |          |         |                 |           |
| 2 |            |          |          |         |                 |           |
| 3 |            |          |          |         |                 |           |
| 4 |            |          |          |         |                 |           |
| 5 |            |          |          |         |                 |           |

**Total actual ad time:** 

### Missed Advertisements (False Negatives)

| # | Start Time | End Time | Duration | Ad Type | Why Missed? |
|---|------------|----------|----------|---------|-------------|
| 1 |            |          |          |         |             |

### False Positives (Incorrectly Flagged)

| # | Start Time | End Time | Duration | What It Actually Was |
|---|------------|----------|----------|----------------------|
| 1 |            |          |          |                      |

### Episode Metrics

- **True Positives (TP):** 
- **False Positives (FP):** 
- **False Negatives (FN):** 
- **Precision:** TP / (TP + FP) = 
- **Recall:** TP / (TP + FN) = 
- **F1 Score:** 2 × (P × R) / (P + R) = 

### Notes / Observations


---

## Episode 8: Up First - [Title]

### Episode Metadata

- **Podcast:** Up First
- **Episode Title:** 
- **Episode Date:** 
- **Total Duration:** 
- **RSS/Source URL:** 

### Detected Advertisements (System Output)

| # | Start Time | End Time | Duration | Speaker Role | Confidence | Notes |
|---|------------|----------|----------|--------------|------------|-------|
| 1 |            |          |          |              |            |       |
| 2 |            |          |          |              |            |       |
| 3 |            |          |          |              |            |       |
| 4 |            |          |          |              |            |       |
| 5 |            |          |          |              |            |       |

**Total detected ad time:** 

### Actual Advertisements (Ground Truth)

| # | Start Time | End Time | Duration | Ad Type | Sponsor/Product | Detected? |
|---|------------|----------|----------|---------|-----------------|-----------|
| 1 |            |          |          |         |                 |           |
| 2 |            |          |          |         |                 |           |
| 3 |            |          |          |         |                 |           |
| 4 |            |          |          |         |                 |           |
| 5 |            |          |          |         |                 |           |

**Total actual ad time:** 

### Missed Advertisements (False Negatives)

| # | Start Time | End Time | Duration | Ad Type | Why Missed? |
|---|------------|----------|----------|---------|-------------|
| 1 |            |          |          |         |             |

### False Positives (Incorrectly Flagged)

| # | Start Time | End Time | Duration | What It Actually Was |
|---|------------|----------|----------|----------------------|
| 1 |            |          |          |                      |

### Episode Metrics

- **True Positives (TP):** 
- **False Positives (FP):** 
- **False Negatives (FN):** 
- **Precision:** TP / (TP + FP) = 
- **Recall:** TP / (TP + FN) = 
- **F1 Score:** 2 × (P × R) / (P + R) = 

### Notes / Observations


---

## Episode 9: Up First - [Title]

### Episode Metadata

- **Podcast:** Up First
- **Episode Title:** 
- **Episode Date:** 
- **Total Duration:** 
- **RSS/Source URL:** 

### Detected Advertisements (System Output)

| # | Start Time | End Time | Duration | Speaker Role | Confidence | Notes |
|---|------------|----------|----------|--------------|------------|-------|
| 1 |            |          |          |              |            |       |
| 2 |            |          |          |              |            |       |
| 3 |            |          |          |              |            |       |
| 4 |            |          |          |              |            |       |
| 5 |            |          |          |              |            |       |

**Total detected ad time:** 

### Actual Advertisements (Ground Truth)

| # | Start Time | End Time | Duration | Ad Type | Sponsor/Product | Detected? |
|---|------------|----------|----------|---------|-----------------|-----------|
| 1 |            |          |          |         |                 |           |
| 2 |            |          |          |         |                 |           |
| 3 |            |          |          |         |                 |           |
| 4 |            |          |          |         |                 |           |
| 5 |            |          |          |         |                 |           |

**Total actual ad time:** 

### Missed Advertisements (False Negatives)

| # | Start Time | End Time | Duration | Ad Type | Why Missed? |
|---|------------|----------|----------|---------|-------------|
| 1 |            |          |          |         |             |

### False Positives (Incorrectly Flagged)

| # | Start Time | End Time | Duration | What It Actually Was |
|---|------------|----------|----------|----------------------|
| 1 |            |          |          |                      |

### Episode Metrics

- **True Positives (TP):** 
- **False Positives (FP):** 
- **False Negatives (FN):** 
- **Precision:** TP / (TP + FP) = 
- **Recall:** TP / (TP + FN) = 
- **F1 Score:** 2 × (P × R) / (P + R) = 

### Notes / Observations


---

## Episode 10: Up First - [Title]

### Episode Metadata

- **Podcast:** Up First
- **Episode Title:** 
- **Episode Date:** 
- **Total Duration:** 
- **RSS/Source URL:** 

### Detected Advertisements (System Output)

| # | Start Time | End Time | Duration | Speaker Role | Confidence | Notes |
|---|------------|----------|----------|--------------|------------|-------|
| 1 |            |          |          |              |            |       |
| 2 |            |          |          |              |            |       |
| 3 |            |          |          |              |            |       |
| 4 |            |          |          |              |            |       |
| 5 |            |          |          |              |            |       |

**Total detected ad time:** 

### Actual Advertisements (Ground Truth)

| # | Start Time | End Time | Duration | Ad Type | Sponsor/Product | Detected? |
|---|------------|----------|----------|---------|-----------------|-----------|
| 1 |            |          |          |         |                 |           |
| 2 |            |          |          |         |                 |           |
| 3 |            |          |          |         |                 |           |
| 4 |            |          |          |         |                 |           |
| 5 |            |          |          |         |                 |           |

**Total actual ad time:** 

### Missed Advertisements (False Negatives)

| # | Start Time | End Time | Duration | Ad Type | Why Missed? |
|---|------------|----------|----------|---------|-------------|
| 1 |            |          |          |         |             |

### False Positives (Incorrectly Flagged)

| # | Start Time | End Time | Duration | What It Actually Was |
|---|------------|----------|----------|----------------------|
| 1 |            |          |          |                      |

### Episode Metrics

- **True Positives (TP):** 
- **False Positives (FP):** 
- **False Negatives (FN):** 
- **Precision:** TP / (TP + FP) = 
- **Recall:** TP / (TP + FN) = 
- **F1 Score:** 2 × (P × R) / (P + R) = 

### Notes / Observations


---

# STUFF YOU SHOULD KNOW (iHeartPodcasts)

---

## Episode 11: Stuff You Should Know - [Title]

### Episode Metadata

- **Podcast:** Stuff You Should Know
- **Episode Title:** 
- **Episode Date:** 
- **Total Duration:** 
- **RSS/Source URL:** 

### Detected Advertisements (System Output)

| # | Start Time | End Time | Duration | Speaker Role | Confidence | Notes |
|---|------------|----------|----------|--------------|------------|-------|
| 1 |            |          |          |              |            |       |
| 2 |            |          |          |              |            |       |
| 3 |            |          |          |              |            |       |
| 4 |            |          |          |              |            |       |
| 5 |            |          |          |              |            |       |

**Total detected ad time:** 

### Actual Advertisements (Ground Truth)

| # | Start Time | End Time | Duration | Ad Type | Sponsor/Product | Detected? |
|---|------------|----------|----------|---------|-----------------|-----------|
| 1 |            |          |          |         |                 |           |
| 2 |            |          |          |         |                 |           |
| 3 |            |          |          |         |                 |           |
| 4 |            |          |          |         |                 |           |
| 5 |            |          |          |         |                 |           |

**Total actual ad time:** 

### Missed Advertisements (False Negatives)

| # | Start Time | End Time | Duration | Ad Type | Why Missed? |
|---|------------|----------|----------|---------|-------------|
| 1 |            |          |          |         |             |

### False Positives (Incorrectly Flagged)

| # | Start Time | End Time | Duration | What It Actually Was |
|---|------------|----------|----------|----------------------|
| 1 |            |          |          |                      |

### Episode Metrics

- **True Positives (TP):** 
- **False Positives (FP):** 
- **False Negatives (FN):** 
- **Precision:** TP / (TP + FP) = 
- **Recall:** TP / (TP + FN) = 
- **F1 Score:** 2 × (P × R) / (P + R) = 

### Notes / Observations


---

## Episode 12: Stuff You Should Know - [Title]

### Episode Metadata

- **Podcast:** Stuff You Should Know
- **Episode Title:** 
- **Episode Date:** 
- **Total Duration:** 
- **RSS/Source URL:** 

### Detected Advertisements (System Output)

| # | Start Time | End Time | Duration | Speaker Role | Confidence | Notes |
|---|------------|----------|----------|--------------|------------|-------|
| 1 |            |          |          |              |            |       |
| 2 |            |          |          |              |            |       |
| 3 |            |          |          |              |            |       |
| 4 |            |          |          |              |            |       |
| 5 |            |          |          |              |            |       |

**Total detected ad time:** 

### Actual Advertisements (Ground Truth)

| # | Start Time | End Time | Duration | Ad Type | Sponsor/Product | Detected? |
|---|------------|----------|----------|---------|-----------------|-----------|
| 1 |            |          |          |         |                 |           |
| 2 |            |          |          |         |                 |           |
| 3 |            |          |          |         |                 |           |
| 4 |            |          |          |         |                 |           |
| 5 |            |          |          |         |                 |           |

**Total actual ad time:** 

### Missed Advertisements (False Negatives)

| # | Start Time | End Time | Duration | Ad Type | Why Missed? |
|---|------------|----------|----------|---------|-------------|
| 1 |            |          |          |         |             |

### False Positives (Incorrectly Flagged)

| # | Start Time | End Time | Duration | What It Actually Was |
|---|------------|----------|----------|----------------------|
| 1 |            |          |          |                      |

### Episode Metrics

- **True Positives (TP):** 
- **False Positives (FP):** 
- **False Negatives (FN):** 
- **Precision:** TP / (TP + FP) = 
- **Recall:** TP / (TP + FN) = 
- **F1 Score:** 2 × (P × R) / (P + R) = 

### Notes / Observations


---

## Episode 13: Stuff You Should Know - [Title]

### Episode Metadata

- **Podcast:** Stuff You Should Know
- **Episode Title:** 
- **Episode Date:** 
- **Total Duration:** 
- **RSS/Source URL:** 

### Detected Advertisements (System Output)

| # | Start Time | End Time | Duration | Speaker Role | Confidence | Notes |
|---|------------|----------|----------|--------------|------------|-------|
| 1 |            |          |          |              |            |       |
| 2 |            |          |          |              |            |       |
| 3 |            |          |          |              |            |       |
| 4 |            |          |          |              |            |       |
| 5 |            |          |          |              |            |       |

**Total detected ad time:** 

### Actual Advertisements (Ground Truth)

| # | Start Time | End Time | Duration | Ad Type | Sponsor/Product | Detected? |
|---|------------|----------|----------|---------|-----------------|-----------|
| 1 |            |          |          |         |                 |           |
| 2 |            |          |          |         |                 |           |
| 3 |            |          |          |         |                 |           |
| 4 |            |          |          |         |                 |           |
| 5 |            |          |          |         |                 |           |

**Total actual ad time:** 

### Missed Advertisements (False Negatives)

| # | Start Time | End Time | Duration | Ad Type | Why Missed? |
|---|------------|----------|----------|---------|-------------|
| 1 |            |          |          |         |             |

### False Positives (Incorrectly Flagged)

| # | Start Time | End Time | Duration | What It Actually Was |
|---|------------|----------|----------|----------------------|
| 1 |            |          |          |                      |

### Episode Metrics

- **True Positives (TP):** 
- **False Positives (FP):** 
- **False Negatives (FN):** 
- **Precision:** TP / (TP + FP) = 
- **Recall:** TP / (TP + FN) = 
- **F1 Score:** 2 × (P × R) / (P + R) = 

### Notes / Observations


---

## Episode 14: Stuff You Should Know - [Title]

### Episode Metadata

- **Podcast:** Stuff You Should Know
- **Episode Title:** 
- **Episode Date:** 
- **Total Duration:** 
- **RSS/Source URL:** 

### Detected Advertisements (System Output)

| # | Start Time | End Time | Duration | Speaker Role | Confidence | Notes |
|---|------------|----------|----------|--------------|------------|-------|
| 1 |            |          |          |              |            |       |
| 2 |            |          |          |              |            |       |
| 3 |            |          |          |              |            |       |
| 4 |            |          |          |              |            |       |
| 5 |            |          |          |              |            |       |

**Total detected ad time:** 

### Actual Advertisements (Ground Truth)

| # | Start Time | End Time | Duration | Ad Type | Sponsor/Product | Detected? |
|---|------------|----------|----------|---------|-----------------|-----------|
| 1 |            |          |          |         |                 |           |
| 2 |            |          |          |         |                 |           |
| 3 |            |          |          |         |                 |           |
| 4 |            |          |          |         |                 |           |
| 5 |            |          |          |         |                 |           |

**Total actual ad time:** 

### Missed Advertisements (False Negatives)

| # | Start Time | End Time | Duration | Ad Type | Why Missed? |
|---|------------|----------|----------|---------|-------------|
| 1 |            |          |          |         |             |

### False Positives (Incorrectly Flagged)

| # | Start Time | End Time | Duration | What It Actually Was |
|---|------------|----------|----------|----------------------|
| 1 |            |          |          |                      |

### Episode Metrics

- **True Positives (TP):** 
- **False Positives (FP):** 
- **False Negatives (FN):** 
- **Precision:** TP / (TP + FP) = 
- **Recall:** TP / (TP + FN) = 
- **F1 Score:** 2 × (P × R) / (P + R) = 

### Notes / Observations


---

## Episode 15: Stuff You Should Know - [Title]

### Episode Metadata

- **Podcast:** Stuff You Should Know
- **Episode Title:** 
- **Episode Date:** 
- **Total Duration:** 
- **RSS/Source URL:** 

### Detected Advertisements (System Output)

| # | Start Time | End Time | Duration | Speaker Role | Confidence | Notes |
|---|------------|----------|----------|--------------|------------|-------|
| 1 |            |          |          |              |            |       |
| 2 |            |          |          |              |            |       |
| 3 |            |          |          |              |            |       |
| 4 |            |          |          |              |            |       |
| 5 |            |          |          |              |            |       |

**Total detected ad time:** 

### Actual Advertisements (Ground Truth)

| # | Start Time | End Time | Duration | Ad Type | Sponsor/Product | Detected? |
|---|------------|----------|----------|---------|-----------------|-----------|
| 1 |            |          |          |         |                 |           |
| 2 |            |          |          |         |                 |           |
| 3 |            |          |          |         |                 |           |
| 4 |            |          |          |         |                 |           |
| 5 |            |          |          |         |                 |           |

**Total actual ad time:** 

### Missed Advertisements (False Negatives)

| # | Start Time | End Time | Duration | Ad Type | Why Missed? |
|---|------------|----------|----------|---------|-------------|
| 1 |            |          |          |         |             |

### False Positives (Incorrectly Flagged)

| # | Start Time | End Time | Duration | What It Actually Was |
|---|------------|----------|----------|----------------------|
| 1 |            |          |          |                      |

### Episode Metrics

- **True Positives (TP):** 
- **False Positives (FP):** 
- **False Negatives (FN):** 
- **Precision:** TP / (TP + FP) = 
- **Recall:** TP / (TP + FN) = 
- **F1 Score:** 2 × (P × R) / (P + R) = 

### Notes / Observations


---

# HAPPIER WITH GRETCHEN RUBIN

---

## Episode 16: Happier - [Title]

### Episode Metadata

- **Podcast:** Happier with Gretchen Rubin
- **Episode Title:** 
- **Episode Date:** 
- **Total Duration:** 
- **RSS/Source URL:** 

### Detected Advertisements (System Output)

| # | Start Time | End Time | Duration | Speaker Role | Confidence | Notes |
|---|------------|----------|----------|--------------|------------|-------|
| 1 |            |          |          |              |            |       |
| 2 |            |          |          |              |            |       |
| 3 |            |          |          |              |            |       |
| 4 |            |          |          |              |            |       |
| 5 |            |          |          |              |            |       |

**Total detected ad time:** 

### Actual Advertisements (Ground Truth)

| # | Start Time | End Time | Duration | Ad Type | Sponsor/Product | Detected? |
|---|------------|----------|----------|---------|-----------------|-----------|
| 1 |            |          |          |         |                 |           |
| 2 |            |          |          |         |                 |           |
| 3 |            |          |          |         |                 |           |
| 4 |            |          |          |         |                 |           |
| 5 |            |          |          |         |                 |           |

**Total actual ad time:** 

### Missed Advertisements (False Negatives)

| # | Start Time | End Time | Duration | Ad Type | Why Missed? |
|---|------------|----------|----------|---------|-------------|
| 1 |            |          |          |         |             |

### False Positives (Incorrectly Flagged)

| # | Start Time | End Time | Duration | What It Actually Was |
|---|------------|----------|----------|----------------------|
| 1 |            |          |          |                      |

### Episode Metrics

- **True Positives (TP):** 
- **False Positives (FP):** 
- **False Negatives (FN):** 
- **Precision:** TP / (TP + FP) = 
- **Recall:** TP / (TP + FN) = 
- **F1 Score:** 2 × (P × R) / (P + R) = 

### Notes / Observations


---

## Episode 17: Happier - [Title]

### Episode Metadata

- **Podcast:** Happier with Gretchen Rubin
- **Episode Title:** 
- **Episode Date:** 
- **Total Duration:** 
- **RSS/Source URL:** 

### Detected Advertisements (System Output)

| # | Start Time | End Time | Duration | Speaker Role | Confidence | Notes |
|---|------------|----------|----------|--------------|------------|-------|
| 1 |            |          |          |              |            |       |
| 2 |            |          |          |              |            |       |
| 3 |            |          |          |              |            |       |
| 4 |            |          |          |              |            |       |
| 5 |            |          |          |              |            |       |

**Total detected ad time:** 

### Actual Advertisements (Ground Truth)

| # | Start Time | End Time | Duration | Ad Type | Sponsor/Product | Detected? |
|---|------------|----------|----------|---------|-----------------|-----------|
| 1 |            |          |          |         |                 |           |
| 2 |            |          |          |         |                 |           |
| 3 |            |          |          |         |                 |           |
| 4 |            |          |          |         |                 |           |
| 5 |            |          |          |         |                 |           |

**Total actual ad time:** 

### Missed Advertisements (False Negatives)

| # | Start Time | End Time | Duration | Ad Type | Why Missed? |
|---|------------|----------|----------|---------|-------------|
| 1 |            |          |          |         |             |

### False Positives (Incorrectly Flagged)

| # | Start Time | End Time | Duration | What It Actually Was |
|---|------------|----------|----------|----------------------|
| 1 |            |          |          |                      |

### Episode Metrics

- **True Positives (TP):** 
- **False Positives (FP):** 
- **False Negatives (FN):** 
- **Precision:** TP / (TP + FP) = 
- **Recall:** TP / (TP + FN) = 
- **F1 Score:** 2 × (P × R) / (P + R) = 

### Notes / Observations


---

## Episode 18: Happier - [Title]

### Episode Metadata

- **Podcast:** Happier with Gretchen Rubin
- **Episode Title:** 
- **Episode Date:** 
- **Total Duration:** 
- **RSS/Source URL:** 

### Detected Advertisements (System Output)

| # | Start Time | End Time | Duration | Speaker Role | Confidence | Notes |
|---|------------|----------|----------|--------------|------------|-------|
| 1 |            |          |          |              |            |       |
| 2 |            |          |          |              |            |       |
| 3 |            |          |          |              |            |       |
| 4 |            |          |          |              |            |       |
| 5 |            |          |          |              |            |       |

**Total detected ad time:** 

### Actual Advertisements (Ground Truth)

| # | Start Time | End Time | Duration | Ad Type | Sponsor/Product | Detected? |
|---|------------|----------|----------|---------|-----------------|-----------|
| 1 |            |          |          |         |                 |           |
| 2 |            |          |          |         |                 |           |
| 3 |            |          |          |         |                 |           |
| 4 |            |          |          |         |                 |           |
| 5 |            |          |          |         |                 |           |

**Total actual ad time:** 

### Missed Advertisements (False Negatives)

| # | Start Time | End Time | Duration | Ad Type | Why Missed? |
|---|------------|----------|----------|---------|-------------|
| 1 |            |          |          |         |             |

### False Positives (Incorrectly Flagged)

| # | Start Time | End Time | Duration | What It Actually Was |
|---|------------|----------|----------|----------------------|
| 1 |            |          |          |                      |

### Episode Metrics

- **True Positives (TP):** 
- **False Positives (FP):** 
- **False Negatives (FN):** 
- **Precision:** TP / (TP + FP) = 
- **Recall:** TP / (TP + FN) = 
- **F1 Score:** 2 × (P × R) / (P + R) = 

### Notes / Observations


---

## Episode 19: Happier - [Title]

### Episode Metadata

- **Podcast:** Happier with Gretchen Rubin
- **Episode Title:** 
- **Episode Date:** 
- **Total Duration:** 
- **RSS/Source URL:** 

### Detected Advertisements (System Output)

| # | Start Time | End Time | Duration | Speaker Role | Confidence | Notes |
|---|------------|----------|----------|--------------|------------|-------|
| 1 |            |          |          |              |            |       |
| 2 |            |          |          |              |            |       |
| 3 |            |          |          |              |            |       |
| 4 |            |          |          |              |            |       |
| 5 |            |          |          |              |            |       |

**Total detected ad time:** 

### Actual Advertisements (Ground Truth)

| # | Start Time | End Time | Duration | Ad Type | Sponsor/Product | Detected? |
|---|------------|----------|----------|---------|-----------------|-----------|
| 1 |            |          |          |         |                 |           |
| 2 |            |          |          |         |                 |           |
| 3 |            |          |          |         |                 |           |
| 4 |            |          |          |         |                 |           |
| 5 |            |          |          |         |                 |           |

**Total actual ad time:** 

### Missed Advertisements (False Negatives)

| # | Start Time | End Time | Duration | Ad Type | Why Missed? |
|---|------------|----------|----------|---------|-------------|
| 1 |            |          |          |         |             |

### False Positives (Incorrectly Flagged)

| # | Start Time | End Time | Duration | What It Actually Was |
|---|------------|----------|----------|----------------------|
| 1 |            |          |          |                      |

### Episode Metrics

- **True Positives (TP):** 
- **False Positives (FP):** 
- **False Negatives (FN):** 
- **Precision:** TP / (TP + FP) = 
- **Recall:** TP / (TP + FN) = 
- **F1 Score:** 2 × (P × R) / (P + R) = 

### Notes / Observations


---

## Episode 20: Happier - [Title]

### Episode Metadata

- **Podcast:** Happier with Gretchen Rubin
- **Episode Title:** 
- **Episode Date:** 
- **Total Duration:** 
- **RSS/Source URL:** 

### Detected Advertisements (System Output)

| # | Start Time | End Time | Duration | Speaker Role | Confidence | Notes |
|---|------------|----------|----------|--------------|------------|-------|
| 1 |            |          |          |              |            |       |
| 2 |            |          |          |              |            |       |
| 3 |            |          |          |              |            |       |
| 4 |            |          |          |              |            |       |
| 5 |            |          |          |              |            |       |

**Total detected ad time:** 

### Actual Advertisements (Ground Truth)

| # | Start Time | End Time | Duration | Ad Type | Sponsor/Product | Detected? |
|---|------------|----------|----------|---------|-----------------|-----------|
| 1 |            |          |          |         |                 |           |
| 2 |            |          |          |         |                 |           |
| 3 |            |          |          |         |                 |           |
| 4 |            |          |          |         |                 |           |
| 5 |            |          |          |         |                 |           |

**Total actual ad time:** 

### Missed Advertisements (False Negatives)

| # | Start Time | End Time | Duration | Ad Type | Why Missed? |
|---|------------|----------|----------|---------|-------------|
| 1 |            |          |          |         |             |

### False Positives (Incorrectly Flagged)

| # | Start Time | End Time | Duration | What It Actually Was |
|---|------------|----------|----------|----------------------|
| 1 |            |          |          |                      |

### Episode Metrics

- **True Positives (TP):** 
- **False Positives (FP):** 
- **False Negatives (FN):** 
- **Precision:** TP / (TP + FP) = 
- **Recall:** TP / (TP + FN) = 
- **F1 Score:** 2 × (P × R) / (P + R) = 

### Notes / Observations


---

# Appendix: Raw Data

*Link to GitHub repository with full JSON payloads for each episode's diarization output.*

**Repository URL:** 

## Data Files

| Episode | Diarization JSON | Transcript JSON |
|---------|------------------|-----------------|
| Episode 1 | | |
| Episode 2 | | |
| Episode 3 | | |
| Episode 4 | | |
| Episode 5 | | |
| Episode 6 | | |
| Episode 7 | | |
| Episode 8 | | |
| Episode 9 | | |
| Episode 10 | | |
| Episode 11 | | |
| Episode 12 | | |
| Episode 13 | | |
| Episode 14 | | |
| Episode 15 | | |
| Episode 16 | | |
| Episode 17 | | |
| Episode 18 | | |
| Episode 19 | | |
| Episode 20 | | |