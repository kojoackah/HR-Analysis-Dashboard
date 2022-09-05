# HR-Analysis-Dashboard

The task was to "play the role of an HR analyst and provide insights on a Human Resources dataset". The data was originally comprised of 22,214 entries, but later after the data processing and data preparation stages, it shrunk to a significant 14,978 records (67.4%) of the original dataset.

One standout issue with this dataset was that after calculating the ages of the employees (using the DOB and hire_date), negative and unreasonable ages (less than 16 years) were computed. To deal with this, I assumed that accurate ages corresponded to the usual age of graduation being 21-22 years. All other calculated ages below that were removed.
