<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVGG3xBQcMr" class="i87az_buj"/></defs><clipPath id="SVGp9tgcbZN"><use href="#SVGG3xBQcMr"/></clipPath><path clip-path="url(#SVGp9tgcbZN)" class="r0w69od8l"/><path clip-path="url(#SVGp9tgcbZN)" class="atwaqtbwi"/><path clip-path="url(#SVGp9tgcbZN)" class="kgkh5ml2f"/><path clip-path="url(#SVGp9tgcbZN)" class="m1x5knbej"/><path clip-path="url(#SVGp9tgcbZN)" class="zeuw_0ckl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:writing-hand" /></template>
<style>
.atwaqtbwi {
  fill: var(--svg-color--006ca0, #006ca0);
  d: path("M6.92 103.33L.76 121.09v1.12s-2.96 7.4 3.3 2.17c.42-.04.85-.19.85-.19s16.8-13.56 17.36-13.74s8.08-12.01 8.08-12.01s-14.25-11.39-16.6-7.78c-2.34 3.59-6.83 12.67-6.83 12.67");
}

.i87az_buj {
  d: path("M.06 0H128v128H.06z");
}

.kgkh5ml2f {
  fill: var(--svg-color--e48c15, #e48c15);
  d: path("M69.96 47.4s-21.87-11.16-31.6-4.14c-8.56 6.18-15.61 9.71-19.92 12.2S7.85 57.47 6.98 69.16c-.74 10.09-.75 18.61-2.36 22.05c-4.56 9.71 7.66 16.34 12.2-1.87c4.66-15.44 18.06-2.24 28.51-4.73c10.46-2.49 29.84-21.24 32.05-26.27c3.04-6.92-7.42-10.94-7.42-10.94");
}

.m1x5knbej {
  fill: var(--svg-color--006ca0, #006ca0);
  d: path("M16.11 85.23S65.82 8.96 70.25 3.98c3.96-4.45.97-4.64 15.39 4.48c3.62 2.29-53.87 80.06-53.87 80.06l-16.56-1.5z");
}

.r0w69od8l {
  fill: var(--svg-color--e48c15, #e48c15);
  d: path("M25.12 96.06s-2.67 14.99 10.96 10.46c22.46-7.47 23.54.68 30.43 3.49c10.29 4.19 21.86 3.73 33.82-9.19C112.79 87.35 68.96 83.61 57 82.36c-11.95-1.24-30.63 13.45-30.63 13.45");
}

.zeuw_0ckl {
  fill: var(--svg-color--fac036, #fac036);
  d: path("M54.3 59.7s-8.47 12.45-18.93 17.43s-23.41 6.97-21.42 15.44s11.95 14.45 27.89 2.49c8.47-5.48 13.45-1 20.92 2.49s8.96 9.46 27.39 6.47s20.26.43 28.39 4.48c7.97-4.98 8.96-19.92 8.96-29.39s-1.15-8.25-12.45-9.46c-8.96-2.99-33.01-14.98-39.44-19.01c-2.59-1.62-8.74-6.08-16.46 2.79");
}

</style>
