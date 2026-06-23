<div align="center">

# move2universe

### Open R tools for animal-movement analysis, built around [`move2`](https://bartk.gitlab.io/move2/)

[![License: GPL (>= 3)](https://img.shields.io/badge/license-GPL%20(%3E%3D%203)-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
&nbsp;[![Built on move2](https://img.shields.io/badge/built%20on-move2-1f6feb.svg)](https://bartk.gitlab.io/move2/)
&nbsp;[![R](https://img.shields.io/badge/R-%E2%89%A5%204.1-1f6feb.svg)](https://www.r-project.org/)

*The central home for the `move2` ecosystem — software, documentation, and learning material.*

</div>

---

`move2universe` is home to a growing family of R packages for working with animal-tracking
data: from the core data structure through sensor data, environmental annotation, and
analysis utilities. They share one design principle — they operate directly on
[`move2`](https://bartk.gitlab.io/move2/) track objects and preserve coordinate reference
systems, track identifiers, timestamps, and metadata — so they compose into a single
workflow rather than each demanding its own data format.

## Packages

| Package | What it does | Where |
|---|---|---|
| [**move2**](https://bartk.gitlab.io/move2/) | The movement-data class — the foundation the rest build on. | [![CRAN](https://www.r-pkg.org/badges/version/move2)](https://cran.r-project.org/package=move2) |
| [**move2utils**](https://github.com/move2universe/move2utils) | Utilisation distributions, corridor detection, and probability-based outlier cleaning. | [GitHub](https://github.com/move2universe/move2utils) |
| [**move2imu**](https://move2universe.github.io/move2imu/) | Working with inertial / accelerometer (IMU) sensor data. | [GitHub](https://github.com/move2universe/move2imu) |
| **move2env** | Environmental annotation of tracks. | *early development* |

New here? Start with **move2** for the data structure, then add the packages you need.
Links point to each package's current home; as the ecosystem consolidates, these will move
under `move2universe`.

## Learning &amp; community

Beyond the code, `move2universe` is where we gather material to help you use these tools well:

- **Vignettes &amp; tutorials** — worked examples ship with each package
  (e.g. `browseVignettes("move2utils")`), with longer-form teaching and learning material
  collected here over time.
- **Help &amp; discussion** — questions, bug reports, and feature ideas are welcome on each
  package's issue tracker; broader community discussion and a shared wiki will grow here as
  the ecosystem does.

## About

<div align="center">

Developed primarily in the **Animal–Environment Interactions Lab** at the<br>
**[Max Planck Institute of Animal Behavior](https://www.ab.mpg.de/)** (Konstanz / Radolfzell, Germany),<br>
with collaborators at the **University of Amsterdam**.

</div>

**Maintainers &amp; contributors**

- **Bart Kranstauber** — University of Amsterdam · lead developer of `move2`
- **Kamran Safi** — Max Planck Institute of Animal Behavior &amp; University of Konstanz
- **Anne K. Scharf** — Max Planck Institute of Animal Behavior &amp; University of Konstanz
- **Finn Roberts** — Max Planck Institute of Animal Behavior

<div align="center">
<sub>Open source under the GPL (&ge; 3). Contributions welcome — see each package's <code>CONTRIBUTING</code> guide.</sub>
</div>
