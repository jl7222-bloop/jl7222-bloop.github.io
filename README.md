# Jiayu Liu — Design portfolio

Website: https://jl7222-bloop.github.io/

The complete static website is stored as split archive files to accommodate browser upload limits. GitHub Actions reassembles the archive and deploys it to GitHub Pages.

To extract the HTML, CSS, JavaScript, images, and videos locally:

```sh
mkdir -p site
cat site.tar.gz.part* | tar -xz -C site
```
