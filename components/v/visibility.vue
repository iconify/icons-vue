<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ndzppditw"/><path class="nqahmx-hk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:visibility" /></template>
<style>
.ndzppditw {
  d: path("M2.5 12C5 7.25 8.25 5.5 12 5.5s7 1.75 9.5 6.5c-2.5 4.75-5.75 6.5-9.5 6.5S5 16.75 2.5 12Z");
}

.nqahmx-hk {
  d: path("M9 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM4 3.5l16 17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
