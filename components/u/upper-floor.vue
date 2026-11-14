<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="us_qbfb0n"/><path class="rs0venbbu"/><path class="z4xqf3bul"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:upper-floor" /></template>
<style>
.rs0venbbu {
  fill: currentColor;
  d: path("M6 8.5h12V13H6Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.us_qbfb0n {
  d: path("M6 21.5v-13L12 3l6 5.5v13");
}

.z4xqf3bul {
  d: path("M2.5 21.5h19M6 17.25h12");
}

</style>
