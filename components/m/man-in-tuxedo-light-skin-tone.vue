<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="SVGB7CPqxWq" x1="64" x2="64" y1="32.155" y2="-2.363" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset=".003" class="aplh-7tkj"/><stop offset=".277" class="mqaun3icq"/><stop offset=".783" class="car3btb1d"/><stop offset="1" class="wk_lp_wlk"/></linearGradient><path fill="url(#SVGB7CPqxWq)" class="hmqldjlhw"/><path class="og1fmqbfq"/><path class="unv60t5tg"/><path class="mj4b7l0lb"/><path class="lc29m76zn"/><path class="c5f366axm"/><g class="vfzj0yb9f"><path class="kvd24db9a"/><path class="mqk2blbhl"/></g><circle class="llb2ncblt"/><path class="xckg1k-tc"/><path class="gil7tbbbf"/><path class="vthnb4bjv"/><g class="edr3jwbtv"><ellipse class="xm_cxnkcf"/><ellipse class="qi4mcqr9e"/></g><path class="npjaz2boe"/><path class="tgg083bvb"/><path class="fvghzkb5q"/><radialGradient id="SVG3Ks2BbwS" cx="64.055" cy="80.901" r="38.092" gradientTransform="matrix(1 0 0 -1.1282 0 138.37)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="x21lzsbti"/><stop offset="1" class="fwx9zn6gv"/></radialGradient><path fill="url(#SVG3Ks2BbwS)" class="w40wa9dgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:man-in-tuxedo-light-skin-tone" /></template>
<style>
.aplh-7tkj {
  stop-color: var(--svg-color--616161, #616161);
}

.c5f366axm {
  fill: var(--svg-color--9e9e9e, #9e9e9e);
  d: path("M51.72 96.57c-.03 0-.07.01-.1.01v-.01c-.11.02-.22.03-.33.05c-3.52.35-6.96.84-10.26 1.5l-3.98 6.36l7.12 4.36l-4.75 6.11l9.3 9.05h8.99zm39.24 7.91l-3.87-6.18c-3.47-.74-7.1-1.3-10.82-1.68L70.31 124h8.99l9.3-9.05l-4.75-6.11z");
}

.car3btb1d {
  stop-color: var(--svg-color--323232, #323232);
}

.edr3jwbtv {
  fill: var(--svg-color--312d2d, #312d2d);
}

.fvghzkb5q {
  fill: var(--svg-color--312d2d, #312d2d);
  d: path("M64.07 4.03h-.04c-45.43.24-36.12 52.14-36.12 52.14s2.04 5.35 2.97 7.71c.13.34.63.3.71-.05c.97-4.34 4.46-19.73 6.22-24.41a6.075 6.075 0 0 1 6.79-3.83c4.45.81 11.55 1.81 19.37 1.81h.16c7.82 0 14.92-1 19.37-1.81c2.9-.53 5.76 1.08 6.79 3.83c1.75 4.66 5.22 19.96 6.2 24.36c.08.36.58.39.71.05l2.98-7.67c.02.01 9.33-51.89-36.11-52.13");
}

.fwx9zn6gv {
  stop-color: var(--svg-color--454140, #454140);
}

.gil7tbbbf {
  fill: var(--svg-color--f9ddbd, #f9ddbd);
  d: path("M64 11.07c-17.4 0-33.52 18.61-33.52 45.4c0 26.64 16.61 39.81 33.52 39.81S97.52 83.1 97.52 56.46c0-26.78-16.12-45.39-33.52-45.39");
}

.hmqldjlhw {
  d: path("M64.14 96H64c-25.65.03-52 7.1-52 24.99V124h104v-3.01C116 104.12 89.9 96 64.14 96");
}

.kvd24db9a {
  d: path("M64.77 115.14h-1.4c-1.53 0-2.85-1.05-3.21-2.54l-.53-2.25a3.3 3.3 0 0 1 3.21-4.06h2.45c2.12 0 3.68 1.97 3.21 4.03l-.51 2.25a3.31 3.31 0 0 1-3.22 2.57");
}

.lc29m76zn {
  fill: var(--svg-color--fff, #fff);
  d: path("M74.27 114.54L64 106s2.94-.06 6.11-4.19c1.86-2.42 3.12-6.03 3.12-6.03l3.14.79z");
}

.llb2ncblt {
  cx: 63.75px;
  cy: 120px;
  r: 2px;
  fill: var(--svg-color--212121, #212121);
}

.mj4b7l0lb {
  fill: var(--svg-color--fff, #fff);
  d: path("M53.75 114.54L64.01 106s-2.94-.06-6.11-4.19c-1.86-2.42-3.12-6.03-3.12-6.03l-3.14.79z");
}

.mqaun3icq {
  stop-color: var(--svg-color--545454, #545454);
}

.mqk2blbhl {
  d: path("M48.79 117.09v-12.07c0-1.5 1.63-2.45 2.95-1.71l10.69 5.94c1.34.74 1.35 2.65.02 3.42l-10.69 6.13c-1.32.74-2.97-.2-2.97-1.71m30 0v-12.07c0-1.5-1.63-2.45-2.95-1.71l-10.69 5.94c-1.34.74-1.35 2.65-.02 3.42l10.69 6.13c1.32.74 2.97-.2 2.97-1.71");
}

.npjaz2boe {
  fill: var(--svg-color--444, #444);
  d: path("M72.42 76.14c-3.18 1.89-13.63 1.89-16.81 0c-1.83-1.09-3.7.58-2.94 2.24c.75 1.63 6.44 5.42 11.37 5.42s10.55-3.79 11.3-5.42c.75-1.66-1.09-3.33-2.92-2.24");
}

.og1fmqbfq {
  fill: var(--svg-color--edc391, #edc391);
  d: path("M64 90.08h-9.08v9.98c0 4.51 3.7 8.17 8.26 8.17h1.65c4.56 0 8.26-3.66 8.26-8.17v-9.98z");
}

.qi4mcqr9e {
  cx: 80.44px;
  cy: 58.81px;
  rx: 4.93px;
  ry: 5.1px;
}

.tgg083bvb {
  fill: var(--svg-color--dba689, #dba689);
  d: path("M67.86 68.06c-.11-.04-.21-.07-.32-.08h-7.08c-.11.01-.22.04-.32.08c-.64.26-.99.92-.69 1.63s1.71 2.69 4.55 2.69s4.25-1.99 4.55-2.69c.3-.71-.05-1.37-.69-1.63");
}

.unv60t5tg {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("m52.66 106l3.85 18H71.9l3.44-18z");
}

.vfzj0yb9f {
  fill: var(--svg-color--212121, #212121);
}

.vthnb4bjv {
  fill: var(--svg-color--454140, #454140);
  d: path("M39.98 50.73c2.99-4.23 9.78-4.63 13.67-1.48c.62.5 1.44 1.2 1.68 1.98c.4 1.27-.82 2.26-2.01 1.96c-.76-.19-1.47-.6-2.22-.83c-1.37-.43-2.36-.55-3.59-.55c-1.82-.01-2.99.22-4.72.92c-.71.29-1.29.75-2.1.41c-.92-.39-1.27-1.58-.71-2.41m46.06 2.4c-.29-.13-.57-.29-.86-.41c-1.78-.74-2.79-.93-4.72-.92c-1.7.01-2.71.24-4.04.69c-.81.28-1.84.98-2.74.71c-1.32-.4-1.28-1.84-.56-2.76c.86-1.08 2.04-1.9 3.29-2.44c2.9-1.26 6.44-1.08 9.17.55c.89.53 1.86 1.26 2.4 2.18c.79 1.3-.4 3.03-1.94 2.4");
}

.w40wa9dgu {
  d: path("M100.2 56.17s9.31-51.9-36.13-52.14h-.04c-.71 0-1.4.02-2.08.05c-1.35.06-2.66.16-3.92.31h-.04c-.09.01-.17.03-.26.04C19.5 9.24 27.91 56.17 27.91 56.17l2.98 7.68c.13.34.62.31.7-.05c.98-4.39 4.46-19.71 6.22-24.37a6.075 6.075 0 0 1 6.79-3.83c4.45.81 11.55 1.81 19.37 1.81h.16c7.82 0 14.92-1 19.37-1.81c2.9-.53 5.76 1.08 6.79 3.83c1.76 4.68 5.25 20.1 6.21 24.42c.08.36.57.39.7.05c.95-2.36 3-7.73 3-7.73");
}

.wk_lp_wlk {
  stop-color: var(--svg-color--212121, #212121);
}

.x21lzsbti {
  stop-color: var(--svg-color--454140, #454140);
  stop-opacity: 0;
}

.xckg1k-tc {
  fill: var(--svg-color--edc391, #edc391);
  d: path("M91.33 50.43H36.67c-5.89 0-10.71 5.14-10.71 11.41s4.82 11.41 10.71 11.41h54.65c5.89 0 10.71-5.14 10.71-11.41s-4.81-11.41-10.7-11.41");
}

.xm_cxnkcf {
  cx: 47.56px;
  cy: 58.81px;
  rx: 4.93px;
  ry: 5.1px;
}

</style>
