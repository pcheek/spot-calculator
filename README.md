# SPOT Revenue Calculator

The SPOT revenue calculator is a basic one page application that calculates
the revenue potential for new SPOT users. When a user enters their address,
the calculator will return the potential monthly revenue based upon their
neighborhood's average.

## Installation

No installation necessary!

## Usage

To use, simply open index.html file in a web browser.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## GIS/Map Data

Map data is used to determine whether the address specified is within the
boundaries of a specific neighborhood. The neighborhood is mapped using Google's
Map Engine Lite and the map is then exported to a .kmz file. The XML body of the
exported .kmz file is then saved within the "data" directory.

The name of each neighborhood in Google Map Engine Lite and in the .kmz file
should match the names within the "spotData" array in the index.html file to
correctly correlate the neighborhood data (such as hourly, daily, weekly, and
monthly revenue potential).

## Credits

Developed by Paul Cheek <paul@paulcheek.com>

## License

...