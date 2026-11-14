<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zaprnqb7t"/><path class="vvttmzbby"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:muscle" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vvttmzbby {
  d: path("M5.5 14c2-.75 4-.5 5.5.5M6 17c2-.5 4-.25 5.5.75");
}

.zaprnqb7t {
  d: path("M2.5 20.5V15c0-3 2-4.75 5-4.75c2 0 3 .75 4 1.25l2-1.5l-.5-3.5c-.25-1.5.75-3 2.5-3h2c1.75 0 2.75 1.25 2.25 3l-1.5 5c-.75 3-1.75 5.5-4.25 7.25C12 20 9.5 20.5 7 20.5Z");
}

</style>
