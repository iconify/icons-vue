<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n8l9ogbkc"/><path class="e_spfzwpz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:oil-field-map" /></template>
<style>
.e_spfzwpz {
  fill: currentColor;
  d: path("M12 2S8.75 6 8.75 8a3.25 3.25 0 0 0 6.5 0c0-2-3.25-6-3.25-6Z");
}

.n8l9ogbkc {
  d: path("M12 14.05V16m4.692-4.231L22 10v10l-6 2l-8-2l-6 2V12l4.459-1.486M8 12.5V20m8-7.5V22");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
