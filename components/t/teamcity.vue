<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVG8OO6qbIH" x1="53.143%" x2="46.484%" y1="67.329%" y2="39.303%"><stop offset="0%" class="xtrtznbzt"/><stop offset="100%" class="gp61sbbkt"/></linearGradient><linearGradient id="SVGhB52cctx" x1="35.784%" x2="66.613%" y1="53.936%" y2="42.814%"><stop offset="0%" class="xtrtznbzt"/><stop offset="100%" class="rwcjds48k"/></linearGradient><linearGradient id="SVGs7PARdlW" x1="73.979%" x2="21.762%" y1="64.146%" y2="35.072%"><stop offset="0%" class="rwcjds48k"/><stop offset="100%" class="gp61sbbkt"/></linearGradient><linearGradient id="SVG6Owguetm" x1="39.629%" x2="64.847%" y1="80.728%" y2="10.287%"><stop offset="30%" class="xtrtznbzt"/><stop offset="60%" class="k_ry59jvu"/></linearGradient></defs><path fill="url(#SVG8OO6qbIH)" class="wg9e-sbtj"/><path fill="url(#SVGhB52cctx)" class="ex8v8d0gw"/><path fill="url(#SVGs7PARdlW)" class="w8vfafb1u"/><path fill="url(#SVG6Owguetm)" class="lwpngaczf"/><path class="rz9-yhbra"/><path class="dpjfyxbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:teamcity" /></template>
<style>
.dpjfyxbyn {
  fill: var(--svg-color--fff, #fff);
  d: path("M67.987 177.752h59.996v10H67.987zm16.132-97.776H65.8V67.764h49.864v12.212h-18.32v47.968H84.12zm36.529 18.544l.002-.652a30.556 30.556 0 0 1 31.385-31.117a31.04 31.04 0 0 1 23.732 9.252l-8.426 9.706a22.24 22.24 0 0 0-15.413-6.8c-10.02 0-17.276 8.24-17.436 18.325l-.003.527c0 10.319 7.147 18.905 17.44 18.905c6.097 0 10.1-2.095 14.236-5.616l.638-.553q.479-.424.965-.87l8.426 8.505a30.8 30.8 0 0 1-24.692 10.666a30.37 30.37 0 0 1-30.854-30.278");
}

.ex8v8d0gw {
  d: path("M226.19 176.606L94.706 247.718a63.6 63.6 0 0 1-88.262-29.863a63.723 63.723 0 0 1 34.238-85.325l138.66-55.993c23.588-9.52 50.627-1.678 65.462 18.984a55.352 55.352 0 0 1-18.612 81.085");
}

.gp61sbbkt {
  stop-color: var(--svg-color--6b57ff, #6b57ff);
}

.k_ry59jvu {
  stop-color: var(--svg-color--3bea62, #3bea62);
}

.lwpngaczf {
  d: path("M37.588 250.198a64.26 64.26 0 0 1-22.878-99.376L129.583 12.01c9.186-11.129 24.684-14.733 37.838-8.799c15.227 6.863 22.657 24.248 17.092 39.996l-59.89 169.928a63.994 63.994 0 0 1-87.035 37.063");
}

.rwcjds48k {
  stop-color: var(--svg-color--009ae5, #009ae5);
}

.rz9-yhbra {
  d: path("M48.041 48.006h159.991v159.983H48.041z");
}

.w8vfafb1u {
  d: path("m176.514 177.832l-135.78-65.62a59.087 59.087 0 0 1-15.998-94.976C43.186-1.206 71.575-5.308 94.492 7.157L227.018 79.15c26.68 14.523 36.732 47.792 22.558 74.658c-13.906 26.38-46.212 37.003-73.062 24.024");
}

.wg9e-sbtj {
  d: path("M65.213 221.374L11.563 80.296A59.03 59.03 0 0 1 65.107.278c26.069-.669 49.486 15.853 57.596 40.636l46.958 143.424c9.466 28.93-93.835 64.98-104.448 37.036");
}

.xtrtznbzt {
  stop-color: var(--svg-color--07c3f2, #07c3f2);
}

</style>
