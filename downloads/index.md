

# Download Julia

If you like Julia, please consider starring us [on GitHub](https://github.com/JuliaLang/julia) and spreading the word!

~~~
<a class="github-button" href="https://github.com/JuliaLang/julia" data-size="large" data-show-count="true" aria-label="Star JuliaLang/julia on GitHub">Star</a>
~~~

We provide several ways for you to run Julia:

@@tight-list
* In the terminal using the built-in Julia command line using the binaries provided below.
* Using [Docker](https://docs.docker.com/) images from [Docker Hub](https://hub.docker.com/_/julia) maintained by the [Docker Community](https://github.com/docker-library/julia).
* [JuliaPro](https://juliacomputing.com/products/juliapro.html) by [Julia Computing](https://juliacomputing.com/) includes Julia and the [Juno IDE](https://junolab.org/), along with access to a curated set of packages for plotting, optimization, machine learning, databases and much more (requires registration).

Please see [platform specific instructions](/downloads/platform/) for further installation instructions and if you have trouble installing Julia.
If the provided download files do not work for you, please [file an issue in the Julia project](https://github.com/JuliaLang/julia/issues).
Different OSes and architectures have varying [tiers of support](/downloads/#currently_supported_platforms), and are listed at the bottom of this page.
@@


## Current stable release: v{{stable_release}} ({{stable_release_date}})

Checksums for this release are available in both [MD5](https://julialang-s3.julialang.org/bin/checksums/julia-{{stable_release}}.md5) and [SHA256](https://julialang-s3.julialang.org/bin/checksums/julia-{{stable_release}}.sha256) formats.

@@row @@col-12
~~~
<table class="downloads table table-hover table-bordered">
  <tbody>
    <tr>
      <th> Windows (.exe) <a href="/downloads/platform/#windows">[help]</a></th>
      <td colspan="3"> <a href="https://julialang-s3.julialang.org/bin/winnt/x86/{{stable_release_short}}/julia-{{stable_release}}-win32.exe">32-bit</a> </td>
      <td colspan="3"> <a href="https://julialang-s3.julialang.org/bin/winnt/x64/{{stable_release_short}}/julia-{{stable_release}}-win64.exe">64-bit</a> </td>
    </tr>
    <tr>
      <th> macOS 10.8+ (.dmg) <a href="/downloads/platform/#macos">[help]</a></th>
      <td colspan="3"> </td>
      <td colspan="3"> <a href="https://julialang-s3.julialang.org/bin/mac/x64/{{stable_release_short}}/julia-{{stable_release}}-mac64.dmg">64-bit</a> </td>
    </tr>
    <tr>
      <th> Generic Linux Binaries for x86 <a href="/downloads/platform/#linux_and_freebsd">[help]</a></th>
      <td colspan="3"> <a href="https://julialang-s3.julialang.org/bin/linux/x86/{{stable_release_short}}/julia-{{stable_release}}-linux-i686.tar.gz">32-bit</a>
        (<a href="https://julialang-s3.julialang.org/bin/linux/x86/{{stable_release_short}}/julia-{{stable_release}}-linux-i686.tar.gz.asc">GPG</a>)
      </td>
      <td colspan="3"> <a href="https://julialang-s3.julialang.org/bin/linux/x64/{{stable_release_short}}/julia-{{stable_release}}-linux-x86_64.tar.gz">64-bit</a>
          (<a href="https://julialang-s3.julialang.org/bin/linux/x64/{{stable_release_short}}/julia-{{stable_release}}-linux-x86_64.tar.gz.asc">GPG</a>)
      </td>
    </tr>
    <tr>
      <th> Generic Linux Binaries for ARM <a href="/downloads/platform/#linux_and_freebsd">[help]</a></th>
      <td colspan="3"> <a href="https://julialang-s3.julialang.org/bin/linux/aarch64/{{stable_release_short}}/julia-{{stable_release}}-linux-aarch64.tar.gz">64-bit (AArch64)</a>
          (<a href="https://julialang-s3.julialang.org/bin/linux/aarch64/{{stable_release_short}}/julia-{{stable_release}}-linux-aarch64.tar.gz.asc">GPG</a>)
      </td>
    </tr>
    <tr>
      <th> Generic FreeBSD Binaries for x86 <a href="/downloads/platform/#linux_and_freebsd">[help]</a></th>
      <td colspan="3"> </td>
      <td colspan="3"> <a href="https://julialang-s3.julialang.org/bin/freebsd/x64/{{stable_release_short}}/julia-{{stable_release}}-freebsd-x86_64.tar.gz">64-bit</a>
          (<a href="https://julialang-s3.julialang.org/bin/freebsd/x64/{{stable_release_short}}/julia-{{stable_release}}-freebsd-x86_64.tar.gz.asc">GPG</a>)
      </td>
    </tr>
    <tr>
      <th> Source </th>
      <td colspan="2"> <a href="https://github.com/JuliaLang/julia/releases/download/v{{stable_release}}/julia-{{stable_release}}.tar.gz">Tarball</a>
            (<a href="https://github.com/JuliaLang/julia/releases/download/v{{stable_release}}/julia-{{stable_release}}.tar.gz.asc">GPG</a>)
      </td>
      <td colspan="2"> <a href="https://github.com/JuliaLang/julia/releases/download/v{{stable_release}}/julia-{{stable_release}}-full.tar.gz">Tarball with dependencies</a>
        (<a href="https://github.com/JuliaLang/julia/releases/download/v{{stable_release}}/julia-{{stable_release}}-full.tar.gz.asc">GPG</a>)
      </td>
      <td colspan="2"> <a href="https://github.com/JuliaLang/julia/tree/v{{stable_release}}">GitHub</a> </td>
    </tr>
  </tbody>
</table>
~~~
@@ @@



## Long-term support (LTS) release: v{{lts_release}} ({{lts_release_date}})

Checksums for this release are available in both, [MD5](https://julialang-s3.julialang.org/bin/checksums/julia-{{lts_release}}.md5) and [SHA256](https://julialang-s3.julialang.org/bin/checksums/julia-{{lts_release}}.sha256) formats.

@@row @@col-12
~~~
<table class="downloads table table-hover  table-bordered">
  <tbody>
    <tr>
      <th> Windows (.exe) <a href="/downloads/platform/#windows">[help]</a></th>
      <td colspan="3"> <a href="https://julialang-s3.julialang.org/bin/winnt/x86/{{lts_release_short}}/julia-{{lts_release}}-win32.exe">32-bit</a> </td>
      <td colspan="3"> <a href="https://julialang-s3.julialang.org/bin/winnt/x64/{{lts_release_short}}/julia-{{lts_release}}-win64.exe">64-bit</a> </td>
    </tr>
    <tr>
      <th> macOS 10.8+ (.dmg) <a href="/downloads/platform/#macos">[help]</a></th>
      <td colspan="3"> </td>
      <td colspan="3"> <a href="https://julialang-s3.julialang.org/bin/mac/x64/{{lts_release_short}}/julia-{{lts_release}}-mac64.dmg">64-bit</a> </td>
    </tr>
    <tr>
      <th> Generic Linux Binaries for x86 <a href="/downloads/platform/#linux_and_freebsd">[help]</a></th>
      <td colspan="3"> <a href="https://julialang-s3.julialang.org/bin/linux/x86/{{lts_release_short}}/julia-{{lts_release}}-linux-i686.tar.gz">32-bit</a>
        (<a href="https://julialang-s3.julialang.org/bin/linux/x86/{{lts_release_short}}/julia-{{lts_release}}-linux-i686.tar.gz.asc">GPG</a>)
      </td>
      <td colspan="3"> <a href="https://julialang-s3.julialang.org/bin/linux/x64/{{lts_release_short}}/julia-{{lts_release}}-linux-x86_64.tar.gz">64-bit</a>
          (<a href="https://julialang-s3.julialang.org/bin/linux/x64/{{lts_release_short}}/julia-{{lts_release}}-linux-x86_64.tar.gz.asc">GPG</a>)
      </td>
    </tr>
    <tr>
      <th> Generic Linux Binaries for ARM <a href="/downloads/platform/#linux_and_freebsd">[help]</a></th>
      <td colspan="3"> <a href="https://julialang-s3.julialang.org/bin/linux/armv7l/{{lts_release_short}}/julia-{{lts_release}}-linux-armv7l.tar.gz">32-bit (ARMv7-a hard float)</a>
        (<a href="https://julialang-s3.julialang.org/bin/linux/armv7l/{{lts_release_short}}/julia-{{lts_release}}-linux-armv7l.tar.gz.asc">GPG</a>)
      </td>
      <td colspan="3"> <a href="https://julialang-s3.julialang.org/bin/linux/aarch64/{{lts_release_short}}/julia-{{lts_release}}-linux-aarch64.tar.gz">64-bit (AArch64)</a>
          (<a href="https://julialang-s3.julialang.org/bin/linux/aarch64/{{lts_release_short}}/julia-{{lts_release}}-linux-aarch64.tar.gz.asc">GPG</a>)
      </td>
    </tr>
    <tr>
      <th> Generic FreeBSD Binaries for x86 <a href="/downloads/platform/#linux_and_freebsd">[help]</a></th>
      <td colspan="3"> </td>
      <td colspan="3"> <a href="https://julialang-s3.julialang.org/bin/freebsd/x64/{{lts_release_short}}/julia-{{lts_release}}-freebsd-x86_64.tar.gz">64-bit</a>
          (<a href="https://julialang-s3.julialang.org/bin/freebsd/x64/{{lts_release_short}}/julia-{{lts_release}}-freebsd-x86_64.tar.gz.asc">GPG</a>)
      </td>
    </tr>
    <tr>
      <th> Source </th>
      <td colspan="2"> <a href="https://github.com/JuliaLang/julia/releases/download/v{{lts_release}}/julia-{{lts_release}}.tar.gz">Tarball</a>
            (<a href="https://github.com/JuliaLang/julia/releases/download/v{{lts_release}}/julia-{{lts_release}}.tar.gz.asc">GPG</a>)
      </td>
      <td colspan="2"> <a href="https://github.com/JuliaLang/julia/releases/download/v{{lts_release}}/julia-{{lts_release}}-full.tar.gz">Tarball with dependencies</a>
        (<a href="https://github.com/JuliaLang/julia/releases/download/v{{lts_release}}/julia-{{lts_release}}-full.tar.gz.asc">GPG</a>)
      </td>
      <td colspan="2"> <a href="https://github.com/JuliaLang/julia/tree/v{{lts_release}}">GitHub</a> </td>
    </tr>
  </tbody>
</table>
~~~
@@ @@

{{ifdef upcoming_release}}

## Upcoming release: v{{upcoming_release}} ({{upcoming_release_date}})

 We're currently testing release candidates for Julia v{{upcoming_release_short}}, an upcoming minor release in the 1.x series of releases. We encourage developers and interested users to try it out and report any issues they encounter. As a prerelease, it should not be considered production-ready; it's intended to give users a chance to try out {{upcoming_release_short}} with their code before the full release.

Checksums for this release are available in both, [MD5](https://julialang-s3.julialang.org/bin/checksums/julia-{{upcoming_release}}.md5) and [SHA256](https://julialang-s3.julialang.org/bin/checksums/julia-{{upcoming_release}}.sha256) formats.

@@row @@col-12
~~~
<table class="downloads table table-hover  table-bordered">
  <tbody>
    <tr>
      <th> Windows Self-Extracting Archive (.exe) <a href="/downloads/platform/#windows">[help]</a></th>
      <td colspan="3"> <a href="https://julialang-s3.julialang.org/bin/winnt/x86/{{upcoming_release_short}}/julia-{{upcoming_release}}-win32.exe">32-bit</a> </td>
      <td colspan="3"> <a href="https://julialang-s3.julialang.org/bin/winnt/x64/{{upcoming_release_short}}/julia-{{upcoming_release}}-win64.exe">64-bit</a> </td>
    </tr>
    <tr>
      <th> macOS 10.8+ Package (.dmg) <a href="/downloads/platform/#macos">[help]</a></th>
      <td colspan="3"> </td>
      <td colspan="3"> <a href="https://julialang-s3.julialang.org/bin/mac/x64/{{upcoming_release_short}}/julia-{{upcoming_release}}-mac64.dmg">64-bit</a> </td>
    </tr>
    <tr>
      <th> Generic Linux Binaries for x86 <a href="/downloads/platform/#linux_and_freebsd">[help]</a></th>
      <td colspan="3"> <a href="https://julialang-s3.julialang.org/bin/linux/x86/{{upcoming_release_short}}/julia-{{upcoming_release}}-linux-i686.tar.gz">32-bit</a>
        (<a href="https://julialang-s3.julialang.org/bin/linux/x86/{{upcoming_release_short}}/julia-{{upcoming_release}}-linux-i686.tar.gz.asc">GPG</a>)
      </td>
      <td colspan="3"> <a href="https://julialang-s3.julialang.org/bin/linux/x64/{{upcoming_release_short}}/julia-{{upcoming_release}}-linux-x86_64.tar.gz">64-bit</a>
        (<a href="https://julialang-s3.julialang.org/bin/linux/x64/{{upcoming_release_short}}/julia-{{upcoming_release}}-linux-x86_64.tar.gz.asc">GPG</a>)
      </td>
    </tr>
    <tr>
      <th> Generic Linux Binaries for ARM <a href="/downloads/platform/#linux_and_freebsd">[help]</a></th>
      <td colspan="3"> Coming soon <!--<a href="https://julialang-s3.julialang.org/bin/linux/armv7l/{{upcoming_release_short}}/julia-{{upcoming_release}}-linux-armv7l.tar.gz">32-bit (ARMv7-a hard float)</a>
                                       (<a href="https://julialang-s3.julialang.org/bin/linux/armv7l/{{upcoming_release_short}}/julia-{{upcoming_release}}-linux-armv7l.tar.gz.asc">GPG</a>) -->
      </td>
      <td colspan="3"> <a href="https://julialang-s3.julialang.org/bin/linux/aarch64/{{upcoming_release_short}}/julia-{{upcoming_release}}-linux-aarch64.tar.gz">64-bit (AArch64)</a>
        (<a href="https://julialang-s3.julialang.org/bin/linux/aarch64/{{upcoming_release_short}}/julia-{{upcoming_release}}-linux-aarch64.tar.gz.asc">GPG</a>)
      </td>
    </tr>
    <tr>
      <th> Generic FreeBSD Binaries for x86 <a href="/downloads/platform/#linux_and_freebsd">[help]</a></th>
      <td colspan="3"> </td>
      <td colspan="3"> <a href="https://julialang-s3.julialang.org/bin/freebsd/x64/{{upcoming_release_short}}/julia-{{upcoming_release}}-freebsd-x86_64.tar.gz">64-bit</a>
        (<a href="https://julialang-s3.julialang.org/bin/freebsd/x64/{{upcoming_release_short}}/julia-{{upcoming_release}}-freebsd-x86_64.tar.gz.asc">GPG</a>)
      </td>
    </tr>
    <tr>
      <th> Source </th>
      <td colspan="2"> <a href="https://github.com/JuliaLang/julia/releases/download/v{{upcoming_release}}/julia-{{upcoming_release}}.tar.gz">Tarball</a>
        (<a href="https://github.com/JuliaLang/julia/releases/download/v{{upcoming_release}}/julia-{{upcoming_release}}.tar.gz.asc">GPG</a>)
      </td>
      <td colspan="2"> <a href="https://github.com/JuliaLang/julia/releases/download/v{{upcoming_release}}/julia-{{upcoming_release}}-full.tar.gz">Tarball with dependencies</a>
        (<a href="https://github.com/JuliaLang/julia/releases/download/v{{upcoming_release}}/julia-{{upcoming_release}}-full.tar.gz.asc">GPG</a>)
      </td>
      <td colspan="2"> <a href="https://github.com/JuliaLang/julia/tree/v{{upcoming_release}}">GitHub</a> </td>
    </tr>
  </tbody>
</table>
~~~
@@ @@

{{end}} <!-- upcoming_release -->


## Older Releases

Older releases of Julia for all platforms are available on the [Older releases page](/downloads/oldreleases/). Only the LTS and Stable releases are maintained.



## Nightly builds

Nightly builds of the current unstable development version of Julia are available on the [nightlies page](/downloads/nightlies/). These are intended as developer previews into the latest work and are not intended for normal use. Most users are advised to use the current release version of Julia, above.



## Download verification

All Julia binary releases are cryptographically secured using the traditional methods on each platform. macOS and Windows releases are codesigned with certificates that are verified by the operating system during installation. Linux and source tarballs are signed with GPG using [this key](/assets/juliareleases.asc).



## Currently supported platforms

The platforms currently supported by Julia are listed below. They are divided into a tier system that ranks them based on level of support.

@@row @@col-12
~~~
<table class="downloads table table-hover ">
  <tbody>
    <tr>
      <th> Operating System </th>
      <th> OS Version </th>
      <th> Architecture </th>
      <th> Support Tier </th>
    </tr>
    <tr>
      <td> macOS </td>
      <td> 10.8+ </td>
      <td> x86-64 (64-bit) </td>
      <td> Tier 1 </td>
    </tr>
    <tr>
      <td rowspan="2"> Windows </td>
      <td rowspan="2"> 7+ </td>
      <td> x86-64 (64-bit) </td>
      <td> Tier 1 </td>
    </tr>
    <tr>

      <td> i686 (32-bit) </td>
      <td> Tier 2 </td>
    </tr>
    <tr>
      <td rowspan="7"> Linux </td>
      <td rowspan="7"> 2.6.18+ </td>
      <td> x86-64 (64-bit) </td>
      <td> Tier 1 </td>
    </tr>
    <tr>

      <td> i686 (32-bit) </td>
      <td> Tier 1 </td>
    </tr>
    <tr>

      <td> Nvidia PTX (64-bit) </td>
      <td> Tier 1 <a href="https://github.com/JuliaGPU/CUDAnative.jl">(External)</a> </td>
    </tr>
    <tr>

      <td> ARMv7 (32-bit) </td>
      <td> Tier 3 </td>
    </tr>
    <tr>

      <td> ARMv8 (64-bit) </td>
      <td> Tier 1 </td>
    </tr>
    <tr>

      <td> x86-64 musl libc </td>
      <td> Tier 3 </td>
    </tr>
    <tr>

      <td> PowerPC (64-bit) </td>
      <td> Tier 3 </td>
    </tr>
    <tr>
      <td rowspan="2"> FreeBSD </td>
      <td rowspan="2"> 11.0+ </td>
      <td> x86-64 (64-bit) </td>
      <td> Tier 1 </td>
    </tr>
    <tr>

      <td> i686 (32-bit) </td>
      <td> Tier 3 </td>
    </tr>
  </tbody>
</table>
~~~
@@ @@

### Support tiers for the latest stable release of Julia

@@tight-list
* **Tier 1**: Julia is guaranteed to build from source and pass all tests on these platforms when built with the default options. Official binaries are always available and CI is run on every commit to ensure support is actively maintained.
* **Tier 2**: Julia is guaranteed to build from source using the default build options, but may or may not pass all tests. Official binaries are available on a case-by-case basis.
* **Tier 3**: Julia may or may not build. If it does, it is unlikely to pass tests. Binaries may be available in some cases. When they are, they should be considered experimental. Ongoing support is dependent on community efforts.
* **Tier 4**: Julia built at some point in the past, but is known not to build currently.
@@
