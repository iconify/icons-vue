<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q3ulk013t"/><path class="xther9roc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:working-hours-law" /></template>
<style>
.q3ulk013t {
  d: path("m12.732 3.404l6.364 6.364l-2.828 2.828l-6.364-6.364ZM16 6.5l4.25-4.25m-6 15.25h7.25v3h-7.25ZM2 15.5a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xther9roc {
  d: path("M6.75 13.5v2l1.75 1");
}

</style>
