<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="dqy0xtbxr"/><path class="nj4wb0axc"/><path clip-rule="evenodd" class="yf3fvnbmi"/><path class="kd31rxf1b"/><path clip-rule="evenodd" class="f00qiwb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:oil-drum" /></template>
<style>
.dqy0xtbxr {
  fill: var(--svg-color--78a3ad, #78a3ad);
  fill-rule: evenodd;
  d: path("M106 64.05c0-1.93-1.01-3.77-2.83-5.47V24.09c1.82-1.7 2.83-3.54 2.83-5.47c0-8.32-18.55-15.06-41.44-15.06S23.13 10.3 23.13 18.62c0 1.93 1.01 3.77 2.83 5.47v34.49c-1.82 1.7-2.83 3.54-2.83 5.47s1.01 3.77 2.83 5.47v34.5c-1.82 1.7-2.83 3.54-2.83 5.47c0 8.32 18.55 15.06 41.44 15.06S106 117.8 106 109.48c0-1.93-1.01-3.77-2.83-5.47v-34.5c1.82-1.69 2.83-3.53 2.83-5.46");
}

.f00qiwb9s {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  fill-rule: evenodd;
  d: path("M46 12c4.42 0 8 1.48 8 3.3s-3.58 3.3-8 3.3s-8-1.48-8-3.3s3.57-3.3 8-3.3");
}

.kd31rxf1b {
  fill: none;
  stroke: var(--svg-color--fff, #fff);
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--3px, 3px);
  d: path("M64.56 30.81c18.03 0 33.19-4.99 37.66-11.77c-6.46 5.54-20.89 9.39-37.66 9.39s-31.2-3.86-37.66-9.39c4.47 6.78 19.64 11.77 37.66 11.77zM26.9 62.94c4.47 6.78 19.64 11.77 37.66 11.77c18.03 0 33.19-4.99 37.66-11.77c-6.46 5.54-20.89 9.39-37.66 9.39s-31.2-3.85-37.66-9.39zm0 46.02c4.47 6.78 19.64 11.77 37.66 11.77c18.03 0 33.19-4.99 37.66-11.77c-6.46 5.54-20.89 9.39-37.66 9.39s-31.2-3.85-37.66-9.39z");
}

.nj4wb0axc {
  fill: none;
  stroke: var(--svg-color--78a3ad, #78a3ad);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--6px, 6px);
  d: path("M106 64.05c0-1.93-1.01-3.77-2.83-5.47V24.09c1.82-1.7 2.83-3.54 2.83-5.47c0-8.32-18.55-15.06-41.44-15.06S23.13 10.3 23.13 18.62c0 1.93 1.01 3.77 2.83 5.47v34.49c-1.82 1.7-2.83 3.54-2.83 5.47s1.01 3.77 2.83 5.47v34.5c-1.82 1.7-2.83 3.54-2.83 5.47c0 8.32 18.55 15.06 41.44 15.06S106 117.8 106 109.48c0-1.93-1.01-3.77-2.83-5.47v-34.5c1.82-1.69 2.83-3.53 2.83-5.46z");
}

.yf3fvnbmi {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M64.56 30.81c18.03 0 33.19-4.99 37.66-11.77c-6.46 5.54-20.89 9.39-37.66 9.39s-31.2-3.86-37.66-9.39c4.47 6.78 19.64 11.77 37.66 11.77M26.9 62.94c4.47 6.78 19.64 11.77 37.66 11.77c18.03 0 33.19-4.99 37.66-11.77c-6.46 5.54-20.89 9.39-37.66 9.39s-31.2-3.85-37.66-9.39m0 46.02c4.47 6.78 19.64 11.77 37.66 11.77c18.03 0 33.19-4.99 37.66-11.77c-6.46 5.54-20.89 9.39-37.66 9.39s-31.2-3.85-37.66-9.39");
}

</style>
