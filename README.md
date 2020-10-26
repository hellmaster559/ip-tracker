# ip-tracker

Need Python 3.7 And Above,


Install The geoip2 From pip:
pip install geoip2


Then, Download The database GeoLite2 City From This Site:
https://dev.maxmind.com/geoip/geoip2/geolite2/   (U Need To Register First)


Then, Paste The Database Path Here (.mmbd file):
r = geoip2.database.Reader(r'*Database Path*')


Done.
