# ApartmentListingsScrapper
Gather data and images from current apartment listings by city. Web scraping code for Apartments.com using python beautiful soup. 

Run the following function to iterate over the pages of a city in Apartments.com, parse_different_links(url = 'https://www.apartments.com/midtown-east-new-york-ny/'). Option to save data as a csv and top 5 images per apartment in a folder called images. 

The following data is gathered per apartment: apartment id, link, name, rent price, number of bedrooms, number of bathrooms, square footage (if available), full description, address, top 5 images, features and amenities, walk score, transit score, bike score, and pet policy.
