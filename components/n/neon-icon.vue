<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGZSjXdboi" x1="100%" x2="12.069%" y1="100%" y2="0%"><stop offset="0%" class="a5g3k2bqw"/><stop offset="100%" class="ebw43bcld"/></linearGradient><linearGradient id="SVGMxAgOWFr" x1="100%" x2="40.603%" y1="100%" y2="76.897%"><stop offset="0%" class="fihwksb4e"/><stop offset="100%" class="ee8lmib0n"/></linearGradient></defs><path class="d3bxpkwws"/><path fill="url(#SVGZSjXdboi)" class="mlc1tplhx"/><path fill="url(#SVGMxAgOWFr)" class="k-xb7-p3t"/><path class="l65eldbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:neon-icon" /></template>
<style>
.a5g3k2bqw {
  stop-color: var(--svg-color--62f755, #62f755);
}

.d3bxpkwws {
  fill: var(--svg-color--00e0d9, #00e0d9);
  d: path("M0 44.139C0 19.762 19.762 0 44.139 0H211.86C236.238 0 256 19.762 256 44.139v142.649c0 25.216-31.915 36.16-47.388 16.256l-48.392-62.251v75.484c0 21.939-17.784 39.723-39.722 39.723h-76.36C19.763 256 0 236.238 0 211.861zm44.139-8.825a8.817 8.817 0 0 0-8.825 8.818v167.73c0 4.878 3.946 8.831 8.818 8.831h77.688c2.44 0 3.087-1.977 3.087-4.416v-101.22c0-25.222 31.914-36.166 47.395-16.255l48.391 62.243V44.14c0-4.879.455-8.825-4.416-8.825z");
}

.ebw43bcld {
  stop-color: var(--svg-color--8ff986, #8ff986);
  stop-opacity: 0;
}

.ee8lmib0n {
  stop-color: var(--svg-color--1a1a1a, #1a1a1a);
  stop-opacity: 0;
}

.fihwksb4e {
  stop-opacity: 0.9;
}

.k-xb7-p3t {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M0 44.139C0 19.762 19.762 0 44.139 0H211.86C236.238 0 256 19.762 256 44.139v142.649c0 25.216-31.915 36.16-47.388 16.256l-48.392-62.251v75.484c0 21.939-17.784 39.723-39.722 39.723h-76.36C19.763 256 0 236.238 0 211.861zm44.139-8.825a8.817 8.817 0 0 0-8.825 8.818v167.73c0 4.878 3.946 8.831 8.818 8.831h77.688c2.44 0 3.087-1.977 3.087-4.416v-101.22c0-25.222 31.914-36.166 47.395-16.255l48.391 62.243V44.14c0-4.879.455-8.825-4.416-8.825z");
}

.l65eldbqf {
  fill: var(--svg-color--63f655, #63f655);
  d: path("M211.861 0C236.238 0 256 19.762 256 44.139v142.649c0 25.216-31.915 36.16-47.388 16.256l-48.392-62.251v75.484c0 21.939-17.784 39.723-39.722 39.723a4.41 4.41 0 0 0 4.409-4.409V115.058c0-25.223 31.914-36.167 47.395-16.256l48.391 62.243V8.825c0-4.871-3.953-8.825-8.832-8.825");
}

.mlc1tplhx {
  d: path("M0 44.139C0 19.762 19.762 0 44.139 0H211.86C236.238 0 256 19.762 256 44.139v142.649c0 25.216-31.915 36.16-47.388 16.256l-48.392-62.251v75.484c0 21.939-17.784 39.723-39.722 39.723h-76.36C19.763 256 0 236.238 0 211.861zm44.139-8.825a8.817 8.817 0 0 0-8.825 8.818v167.73c0 4.878 3.946 8.831 8.818 8.831h77.688c2.44 0 3.087-1.977 3.087-4.416v-101.22c0-25.222 31.914-36.166 47.395-16.255l48.391 62.243V44.14c0-4.879.455-8.825-4.416-8.825z");
}

</style>
