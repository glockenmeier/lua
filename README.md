# lua
Unofficial repository containing all publicly available Lua source code.

This repository represents the Lua version history since Lua 1.0. The codes are commited in order from their first version to the lastest.

You can find the original source here: http://www.lua.org/ftp/
And their version history: http://www.lua.org/versions.html

## Original README:
>To accompany the presentation of the evolution of Lua at HOPL III,
>here are all releases of Lua. Only the source code is included; for
>documentation and other files, see the original tarballs at Lua.org.

>The code has been slightly updated to compile and run with gcc 4. As a
>testimony to the portability of Lua, the required changes were minimal:
>just a trivial change in iolib.c before Lua 2.5. The differences between
>the original code and the updated code are in DIFFS in each directory.

>No attempt has been made to ensure warning-free compilations. A few,
>mostly trivial, changes would be needed for that, but it is interesting
>to see the number of warnings decrease to zero in later versions.

>To build each release, just go its directory and type 'make'. This will
>run a simple test for lua and luac (when available). To build and test
>all releases, just type 'make' at the top level directory.

>The simple Makefiles build Lua without any special options. For those,
>see the original tarballs.

>Lua 3.2 may crash when run if compiled with gcc 4. It runs fine in earlier gcc.

>Enjoy!
>-- The Lua team

_________________________________________________________________

### Lua License

   Lua  is  free  software:  it  can  be  used for any purpose, including
   commercial   purposes,   at  absolutely  no  cost.  No  paperwork,  no
   royalties,  no GNU-like "copyleft" restrictions, either. Just download
   it and use it. Lua is certified Open Source software. Its licenses are
   compatible with GPL. Lua is not in the public domain and PUC-Rio keeps
   its copyright. The legal details are below.

   [osi certified]   License for Lua 5.0 and later versions:
   Since Lua 5.0, Lua is licensed under the terms of the MIT license
   reproduced below.

   [open source]   License for Lua 4.0 and earlier versions:
   Until  Lua  4.0, Lua used its own license, which was very close to the
   zlib license and others, but not quite the same.

   The  spirit  of  both licenses is that you are free to use Lua for any
   purpose  at  no cost without having to ask us. The only requirement is
   that  if  you  do use Lua, then you should give us credit by including
   the  appropriate  copyright  notice  somewhere  in your product or its
   documentation.  A nice, but optional, way to give us further credit is
   to  include  a  Lua logo and a link to our site in a web page for your
   product.

   The  Lua language is entirely designed, implemented, and maintained by
   a  team  at  PUC-Rio in Brazil. The implementation is not derived from
   licensed software.
_________________________________________________________________

### License for Lua 5.0 and later versions

   Copyright © 1994-2015 Lua.org, PUC-Rio.

   Permission  is hereby granted, free of charge, to any person obtaining
   a  copy  of  this  software  and  associated  documentation files (the
   "Software"),  to  deal  in the Software without restriction, including
   without  limitation  the  rights to use, copy, modify, merge, publish,
   distribute,  sublicense,  and/or  sell  copies of the Software, and to
   permit  persons to whom the Software is furnished to do so, subject to
   the following conditions:

   The  above  copyright  notice  and  this  permission  notice  shall be
   included in all copies or substantial portions of the Software.

   THE  SOFTWARE  IS  PROVIDED  "AS  IS",  WITHOUT  WARRANTY OF ANY KIND,
   EXPRESS  OR  IMPLIED,  INCLUDING  BUT NOT LIMITED TO THE WARRANTIES OF
   MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
   IN  NO  EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
   CLAIM,  DAMAGES  OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
   TORT  OR  OTHERWISE,  ARISING  FROM,  OUT OF OR IN CONNECTION WITH THE
   SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
_________________________________________________________________

### License for Lua 4.0 and earlier versions

   Copyright © 1994-2002 Tecgraf, PUC-Rio.

   Permission  is  hereby  granted, without written agreement and without
   license  or  royalty  fees,  to  use,  copy,  modify,  translate,  and
   distribute  this  software  and  its  documentation (hereby called the
   "package") for any purpose, including commercial applications, subject
   to the following conditions:
     * The above copyright notice and this permission notice shall appear
       in all copies or substantial portions of this package.
     * The  origin  of  this package must not be misrepresented; you must
       not  claim  that  you  wrote the original package. If you use this
       package   in   a   product,   an  acknowledgment  in  the  product
       documentation   would  be  greatly  appreciated  (but  it  is  not
       required).
     * Altered  source  versions must be plainly marked as such, and must
       not be misrepresented as being the original package.

   The  authors  specifically disclaim any warranties, including, but not
   limited  to, the implied warranties of merchantability and fitness for
   a  particular purpose. The package provided hereunder is on an "as is"
   basis,  and  the  authors  have  no obligation to provide maintenance,
   support,  updates,  enhancements,  or modifications. In no event shall
   Tecgraf,  PUC-Rio,  or  the  authors  be  held liable to any party for
   direct,   indirect,  special,  incidental,  or  consequential  damages
   arising out of the use of this package and its documentation.
_________________________________________________________________

(license text adapted from http://www.lua.org/license.html)
