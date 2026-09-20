<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="SVGWLabcbkN" x1="64.005" x2="64.005" y1="32.9" y2="5.004" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="zs84mcc3v"/><stop offset=".705" class="fwmih7b7q"/><stop offset="1" class="xv220cbff"/></linearGradient><path fill="url(#SVGWLabcbkN)" class="dlf_t2_gq"/><path class="hksw5er9a"/><path class="x5cpveb2k"/><path class="o5bqwebnw"/><g class="d2ol71wkq"><ellipse class="unukiyudw"/><ellipse class="uc8_0gt2x"/></g><path class="azhty_zwd"/><path class="hk7263b7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:man-bald-dark-skin-tone" /></template>
<style>
.azhty_zwd {
  fill: var(--svg-color--33251f, #33251f);
  d: path("M67.85 68.06c-.11-.04-.21-.07-.32-.08h-7.07c-.11.01-.22.04-.32.08c-.64.26-.99.92-.69 1.63s1.71 2.69 4.55 2.69s4.25-1.99 4.55-2.69c.29-.71-.06-1.37-.7-1.63");
}

.d2ol71wkq {
  fill: var(--svg-color--1a1717, #1a1717);
}

.dlf_t2_gq {
  d: path("M64.13 94.68H64c-25.49.03-51.13 7.5-51.13 25.28v4h102.27v-4c-.01-16.76-25.41-25.28-51.01-25.28");
}

.fwmih7b7q {
  stop-color: var(--svg-color--00b29a, #00b29a);
}

.hk7263b7z {
  fill: var(--svg-color--1a1717, #1a1717);
  d: path("M72.42 76.14c-3.19 1.89-13.63 1.89-16.81 0c-1.83-1.09-3.7.58-2.94 2.24c.75 1.63 6.45 5.42 11.37 5.42s10.55-3.79 11.3-5.42c.75-1.66-1.09-3.33-2.92-2.24");
}

.hksw5er9a {
  fill: var(--svg-color--3c2b24, #3c2b24);
  d: path("M73.08 90.08H54.92v9.98c0 4.51 3.7 8.17 8.26 8.17h1.65c4.56 0 8.26-3.66 8.26-8.17v-9.98zM36.67 72.26c-5.36 0-9.71-4.67-9.71-10.41s4.36-10.41 9.71-10.41h54.65c5.36 0 9.71 4.67 9.71 10.41s-4.36 10.41-9.71 10.41z");
}

.o5bqwebnw {
  fill: var(--svg-color--1a1717, #1a1717);
  d: path("M39.82 50.73c3.18-4.51 10.66-4.66 14.41-.82c.65.67 1.34 1.53.85 2.5c-.54 1.07-1.65.9-2.56.53c-2.43-.98-4.94-1.42-7.55-.89c-1.13.23-2.1.7-3.17 1.08c-1.44.49-2.91-1.01-1.98-2.4m46.45 2.4c-2.23-.97-4.49-1.53-6.95-1.25c-1.12.13-2.22.42-3.26.83c-.83.33-1.72.86-2.58.28c-2.45-1.69 1.89-4.44 3.17-4.99c2.76-1.19 6.05-1.08 8.72.31c1.06.55 2.21 1.35 2.84 2.4c.79 1.31-.39 3.05-1.94 2.42");
}

.uc8_0gt2x {
  cx: 80.63px;
  cy: 58.81px;
  rx: 4.93px;
  ry: 5.1px;
}

.unukiyudw {
  cx: 47.37px;
  cy: 58.81px;
  rx: 4.93px;
  ry: 5.1px;
}

.x5cpveb2k {
  fill: var(--svg-color--70534a, #70534a);
  d: path("M64 11.07c-24 0-33.52 16.09-33.52 42.43c0 26.64 16.61 41.77 33.52 41.77S97.52 80.14 97.52 53.5C97.52 26.72 88 11.07 64 11.07");
}

.xv220cbff {
  stop-color: var(--svg-color--00ab94, #00ab94);
}

.zs84mcc3v {
  stop-color: var(--svg-color--00bfa5, #00bfa5);
}

</style>
