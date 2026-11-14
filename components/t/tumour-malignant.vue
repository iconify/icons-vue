<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qqdyawbeq"/><path class="onj55hh8e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tumour-malignant" /></template>
<style>
.onj55hh8e {
  d: path("M16.75 10.25C18.5 9.5 19.5 8 21.5 8m-7 8c1 2 3 2.5 4 5M7.25 12.25C5.5 13 4 12.5 2.5 13.5m5.5 2c-1.25 1.75-1.5 4-3.5 5.5");
}

.qqdyawbeq {
  d: path("M12 6.25C13.5 6 14.5 7 14.25 8c1.5-.25 2.75.75 2.5 2.25C18 11 18 13 16.75 13.5c.5 1.5-.75 3-2.25 2.5c-.5 1.5-2.5 2-3.5.75c-1.25 1-3 .25-3-1.25c-1.5-.5-2-2.25-.75-3.25C6 11 7 9.25 8.5 9.25c0-1.5 1.5-2.5 2.75-2c.25-.5.25-.75.75-1Zm0 0c-.5-1.75.5-2.75 0-3.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
