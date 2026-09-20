<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="n0f5r9b6r"/><path class="y-kq77bgf"/><path class="d_amrgkqt"/><ellipse class="n6d2x5b3j"/><ellipse transform="rotate(-64.093 63.996 64)" class="f2rtvnxhp"/><path class="bdyz1fb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:nazar-amulet" /></template>
<style>
.bdyz1fb5g {
  fill: var(--svg-color--00cfff, #00cfff);
  d: path("M26.93 35.09c-2.21-.45-5.87-4.73 1.97-11.37c8.65-7.33 14.12-6.89 15.36-5.84c1.99 1.67.57 4.15-3.51 7.08c-6.64 4.75-7.84 11.34-13.82 10.13m-5.13 1.33c5.37.73.01 8.34-1.95 10.05c-.37.32-2.17 1.45-3.69.88s-1.07-3.62-.82-4.76c.64-2.87 2.85-6.66 6.46-6.17");
  opacity: var(--svg-opacity--0-55, 0.55);
}

.d_amrgkqt {
  fill: var(--svg-color--f5f5f5, #f5f5f5);
  d: path("M31.1 64.92c0-18.77 15.86-37.16 32.12-37.16s30.91 15.5 33.5 37.16c2.24 18.76-15.67 37.39-36.23 35.13C39.66 97.76 31.1 83.7 31.1 64.92");
}

.f2rtvnxhp {
  cx: 64px;
  cy: 64px;
  fill: var(--svg-color--212121, #212121);
  rx: 9.16px;
  ry: 8.53px;
}

.n0f5r9b6r {
  fill: var(--svg-color--1851ed, #1851ed);
  d: path("M6.22 61.05C9.72 21.94 45.89 4 65.89 4c26.66 0 54.29 22.01 55.96 60c2.85 33.01-22.82 60-55.96 60S2.65 101.02 6.22 61.05");
}

.n6d2x5b3j {
  cx: 64px;
  cy: 64px;
  fill: var(--svg-color--5ac7f0, #5ac7f0);
  rx: 19.96px;
  ry: 20.68px;
}

.y-kq77bgf {
  fill: var(--svg-color--002691, #002691);
  d: path("M117.51 53.87c-1.63-5.5-6.38-11.11-12.46-10.91c-6.76.54-11.87 5.32-17.22 8.98c-15.95 10.89-34.27 18.29-53.3 21.55c-4.18.72-17.9 2.94-19.68 10.84c-1.18 5.24.92 11.77 5.02 15.82c8.86 8.74 16.03 12.23 20.08 13.61c1.23.42 2.28-.96 1.57-2.04c-1.23-1.86-2.5-4.03-2.22-4.69c1.67-3.91 10.88 1.96 16.32 2.92c12.24 2.15 16.94.06 25.03-2.44c2.28-.7 6.56-2.71 8.6-1.59c2.37 1.3-2.43 6.64-5.54 9.74c-.7.7.05 1.85.98 1.52c9.41-3.36 29.59-18.13 33.44-42.26c1.09-6.71 1.53-14.42-.62-21.05");
  opacity: var(--svg-opacity--0-77, 0.77);
}

</style>
