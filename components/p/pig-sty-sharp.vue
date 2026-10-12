<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="qa9f_xduq"/><path class="zwiybib1x"/><path class="kgvnrnpay"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pig-sty-sharp" /></template>
<style>
.kgvnrnpay {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 10.75h.01m6.49 0h.01");
}

.qa9f_xduq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.72 10.35L4.25 4l4.47 1.98a7.75 7.75 0 0 1 6.56 0L19.75 4l-.47 6.35a7.75 7.75 0 1 1-14.56 0Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zwiybib1x {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 15.25a3.5 2.5 0 1 0 7 0a3.5 2.5 0 1 0-7 0Zm2.25-.75V16m2.5-1.5V16");
}

</style>
