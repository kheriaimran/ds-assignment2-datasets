# ds-assignment2-datasets

Netflix: cleaned from https://www.kaggle.com/datasets/shivamb/netflix-shows
(credit to the original author; follow its licence).
Changes: missing director, cast, country and rating filled with "Unknown";
3 durations found in rating moved to duration; date_added stripped and
converted to datetime (10 left missing). Added columns: year_added,
month_added, n_countries, n_genres, movie_minutes, seasons, gap_years.

Supermarket Sales: cleaned from the file provided by the instructor.
Changes: Time converted to time type; no missing values, duplicates or
label errors found. Added columns: Hour, Weekday, Month.
