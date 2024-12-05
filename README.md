# Coding-Challenge-for-Protect-Data-

The `final_df` dataset is a cleaned and summarized data frame prepared after merging, mapping, and processing participant-level HAM (Hamilton scale) data from both the `HAM_protect` and `HAM_sleep` datasets. This data frame was created following a series of data management steps including ID mapping, score calculation, and selection of relevant visits. The primary goal was to generate a concise, participant-level summary that collaborators in the lab can easily use for further analysis or reporting.

**Contents of `final_df`:**

- **new_id:** A unique identifier for each research participant. This `new_id` has been standardized across data sources, ensuring that each participant can be reliably linked to other study data.

- **mean_score:** The average (mean) HAM score across all available visits for each participant. This score provides an overall indication of the participant’s typical severity level over their recorded visits.

- **latest_score:** The participant’s most recent HAM score recorded in the dataset. This metric allows researchers to see the participant’s status at their latest point of contact.

- **score_closest_1y:** The HAM score from the visit closest to one year after the participant’s first consent date. This value offers insight into how participants may change or stabilize over a one-year period, making it particularly useful for longitudinal studies or time-sensitive interventions.
