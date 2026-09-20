<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="h3h3vub-e"/><circle class="y2uc7vt8s"/><circle class="y2uc7vt8s"/><path class="z1j8-wbhj"/><path class="m2ect3b8k"/><path class="htkbx_3nf"/><path class="no9e7kbwi"/><path class="i06n6hbtr"/><path class="pkwv8jbnf"/><path class="r67pf2byd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:timer-clock" /></template>
<style>
.h3h3vub-e {
  fill: var(--svg-color--b9e4ea, #b9e4ea);
  d: path("m118 60.5l3.48 53.01a7.5 7.5 0 0 1-7.49 7.99H14.01c-4.34 0-7.77-3.67-7.49-7.99L10 60.5c3-34 24.18-54 54-54s50 24 54 54");
}

.htkbx_3nf {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("M64 91.5c-7.18 0-13-5.82-13-13v-35c0-7.18 5.82-13 13-13s13 5.82 13 13v35c0 7.18-5.82 13-13 13");
}

.i06n6hbtr {
  fill: var(--svg-color--f5f5f5, #f5f5f5);
  d: path("M31.58 97.55c.1.1.2.2.3.31c5.02 5.19 11.56 8.68 16.82 13.62c-2.88.99-6.05.33-8.96-.55c-10.89-3.31-21.21-10.15-26.19-20.39c-1.19-2.44-2.07-5.12-1.83-7.82c.13-1.5.73-3.13 2.1-3.78c1.19-.57 2.67-.21 3.74.56c2.62 1.88 3.91 5.96 5.84 8.55c2.49 3.35 5.28 6.48 8.18 9.5");
}

.m2ect3b8k {
  fill: none;
  stroke: var(--svg-color--78909c, #78909c);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--3px, 3px);
  d: path("M64 18.5v8.23m0 67.54v8.23m42-42h-8.23m-67.54 0H22m42-42v8.23m0 67.54v8.23M43 24.13l4.11 7.12m33.78 58.5L85 96.87M43 24.13l4.11 7.12m33.78 58.5L85 96.87M27.63 39.5l7.12 4.11m58.5 33.78l7.12 4.11M85 24.13l-4.11 7.12m-33.78 58.5L43 96.87m57.37-57.37l-7.12 4.11m-58.5 33.78l-7.12 4.11");
}

.no9e7kbwi {
  fill: var(--svg-color--78909c, #78909c);
  d: path("M76.88 42.67c-.55-5.58-3.31-8.85-8.11-11.41c-.5-.27-1.05-.54-1.61-.45c0 0-1.17 42.34-1.17 46.53c0 4.54-.38 9.74-5.56 11.32c-.93.28-1.93.41-2.71.98c3.56 3.1 9.27 2.63 13.12-.09C72.96 88.06 77 85.5 77 74.5");
  opacity: var(--svg-opacity--0-52, 0.52);
}

.pkwv8jbnf {
  fill: var(--svg-color--82aec0, #82aec0);
  d: path("M109.3 84.9c-7.63 13.26-20.53 23.52-35.33 27.52c3.37 4.12 18.9 3.22 29.97-5.1s14.84-30.31 12.47-37.07c-1.16.33-1.64 1.67-1.99 2.82c-1.24 4.13-2.97 8.1-5.12 11.83");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.r67pf2byd {
  fill: var(--svg-color--ff4638, #ff4638);
  d: path("m63.5 16.5l-5-10h11z");
}

.y2uc7vt8s {
  cx: 64px;
  cy: 60.5px;
  r: 40px;
  fill: var(--svg-color--fff, #fff);
}

.z1j8-wbhj {
  fill: var(--svg-color--78909c, #78909c);
  d: path("M64 20.5c22.09 0 40 17.91 40 40s-17.91 40-40 40s-40-17.91-40-40s17.91-40 40-40m0-3c-23.71 0-43 19.29-43 43s19.29 43 43 43s43-19.29 43-43s-19.29-43-43-43");
}

</style>
