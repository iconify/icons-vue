<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<radialGradient id="SVGmEtriegh" cx="63.864" cy="63.865" r="59.778" gradientUnits="userSpaceOnUse"><stop offset="0" class="a72as_i6q"/><stop offset=".617" class="h-fdxew3p"/><stop offset=".848" class="d5o-7dbzj"/><stop offset=".961" class="dl6xs1b4m"/></radialGradient><path fill="url(#SVGmEtriegh)" class="jhhrlcbcj"/><path class="yny0cxb1b"/><path class="lr2lvs6ug"/><path class="inup7yg1w"/><path class="fl8fxub4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:radio-button" /></template>
<style>
.a72as_i6q {
  stop-color: var(--svg-color--424242, #424242);
}

.d5o-7dbzj {
  stop-color: var(--svg-color--4b4b4b, #4b4b4b);
}

.dl6xs1b4m {
  stop-color: var(--svg-color--525252, #525252);
}

.fl8fxub4p {
  fill: var(--svg-color--848484, #848484);
  d: path("M39.96 14.78c-1.25-1.7-6.61-.32-12.74 5.16c-5.15 4.61-7.74 10.48-5.81 12.17c1.94 1.69 6.452-4.417 10.722-8.287S42.21 17.85 39.96 14.78m70.55 69.59c-3.32-1.18-4.51 4.22-6.05 6.69c-6.93 11.13-16.53 16.46-22.17 18.95c-3.47 1.53-6.61 1.61-5.56 5c.81 2.61 6.45.41 8.39-.4c3.47-1.45 10.16-5.17 15.4-9.92c5.08-4.6 8.303-9.216 10.16-13.87c.765-1.918 1.957-5.29-.17-6.45");
}

.h-fdxew3p {
  stop-color: var(--svg-color--444, #444);
}

.inup7yg1w {
  fill: var(--svg-color--fff, #fff);
  d: path("M38.366 59.253c2.003.649 3.35-6.132 10.339-11.758c6.98-5.619 14.603-5.947 14.41-9.113s-8.23-2.58-13.12.32c-4.785 2.846-8.984 6.525-11.309 12.28c-1.346 3.325-1.82 7.79-.32 8.27");
}

.jhhrlcbcj {
  d: path("M63.87 4.1C23.86 5.15 2.21 34.84 4.22 67.67C6.08 98.01 31.27 124.21 65 123.64c36.88-.63 57.52-29.12 58.6-59.18C124.8 31.29 96.46 3.24 63.87 4.1");
}

.lr2lvs6ug {
  fill: var(--svg-color--e0e0e0, #e0e0e0);
  d: path("M63.757 32.178c-20.815.545-31.827 16.006-30.954 33.607c.762 15.469 14.427 29.014 31.98 28.717C83.97 94.174 94.558 80.268 95.27 63.71c.738-17.264-14.555-31.98-31.514-31.53");
}

.yny0cxb1b {
  fill: var(--svg-color--1c1c1c, #1c1c1c);
  d: path("M64.18 26.082c-24.708.66-38.402 19.787-37.425 40.446c.88 18.696 17.14 35.608 37.954 34.695c21.253-.928 35.24-17.547 36.194-37.212c1.002-20.846-16.602-38.467-36.724-37.929");
}

</style>
