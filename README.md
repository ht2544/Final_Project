# Final_Project
This is the final project of group 33 for the course Tools for Analytics.
We are trying to create a website that can track squirells in the Central Park of the New York City.
The data used in our project is from https://data.cityofnewyork.us/api/views/vfnx-vebw/rows.csv.

# Members
Our group is group 33.

Our Unis are "UNIs: [ht2544, sr3761]".

# Management commands
Import data:
```
- $ python manage.py import_squirrel_data /path/to/file.csv
```

Export data:
```
- $ python manage.py export_squirrel_data /path/to/file.csv
```

# Views
## /map
A view that shows a map that displays the location of the squirrel sightings.

## /sightings
A view that lists all squirrel sightings with links to view each single sighting.
 
## /sightings/add
A view to create a new sighting.

## /sightings/stats
A view with general stats about the sightings.
