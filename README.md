## doctopaper
This script tries to convert any document to PDF and open it with the default PDF viewer. Depends on LibreOffice.

The intended use is to open Office files (especially DOC/DOCX) with the Paper app on Droidian.

### Installation
See the [releases](https://github.com/thomashastings/doctopaper/releases) for a downloadable `*.deb` package.
It can be installed by running `sudo apt install ./doctopaper.deb`

You can also use the repository to build it locally:
```
git clone https://github.com/thomashastings/doctopaper.git
cd doctopaper
dpkg-deb --build doctopaper/
sudo apt install ./doctopaper.deb
```

### License
This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License version 3, as published by the Free Software Foundation.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranties of MERCHANTABILITY, SATISFACTORY QUALITY, or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.  If not, see http://www.gnu.org/licenses/.
