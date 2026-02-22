# Minor-Planet-Dataset
### All of the 25k Minor planets in a single json file!

This dataset has all of these fields for every body:

code: The code of the minor planet

name: The name of the minor planet

second_name: The alternative alias of the minor planet

image: The image of the body as a URL. NOTE: Most of the images may not work as they just simply might not exist. But the most notable bodies have working images.

diameter_km: The diameter of the body, in km

radius_km: The radius of the body, in km

size_data_source: Uncludes the source of the size data, most of them are estimated by data, such as magnitude

semi_major_axis_au: The average distance from the body to the Sun, representing the longest radius of its elliptical orbit. Measured in Astronomical Units

eccentricity: A measure of how much the orbit deviates from a perfect circle. A value of 0 is a circle; values closer to 1 indicate a highly elongated (stretched) ellipse.

inclination_deg: The vertical tilt of the orbit relative to the ecliptic plane (the plane of Earth's orbit), measured in degrees (∘).

longitude_ascending_node_deg: The angle in the ecliptic plane where the body crosses from south to north. Think of this as the "compass heading" for where the orbit's tilt begins.

argument_perihelion_deg: The angle that defines the orientation of the elliptical orbit within its own orbital plane—specifically, the angle from the ascending node to the perihelion (closest point to the Sun).

mean_anomaly_deg: A mathematical value used to define the specific position of the body along its orbital path at a specific point in time (the epoch).

perihelion_dist_au: The specific distance of the body from the Sun at its closest approach. Calculated as q=a(1−e).

moid_au: Minimum Orbit Intersection Distance. This is the calculated shortest distance between the orbit of the minor planet and the orbit of Earth. It is used to assess potential impact risks.

orbital_period_days: The total time it takes for the body to complete one full revolution around the Sun, expressed in Earth days.

orbital_period_years: The orbital period expressed in Earth years.

orbital_period_human: A user-friendly, "readable" string combining years and days for easier comprehension.

orbital_data_source: Indicates whether the orbital parameters are confirmed through direct observation or calculated via mathematical estimation.

Made with love, for all of the space nerds out there <3

-Asier
