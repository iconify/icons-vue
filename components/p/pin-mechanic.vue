<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s3n8rxaml"/><path class="yrlhrsb0j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-mechanic" /></template>
<style>
.s3n8rxaml {
  d: path("m7.25 14.25l5-5a3.75 3.75 0 0 1 5-4.75L14.5 7.25l2.25 2.25l2.75-2.75a3.75 3.75 0 0 1-4.75 5l-5 5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yrlhrsb0j {
  d: path("M4.25 17a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Z");
}

</style>
