<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n3z7occ2n"/><path class="uzjoexb_i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mentor" /></template>
<style>
.n3z7occ2n {
  d: path("m3.5 6l5-2.5l5 2.5l-5 2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uzjoexb_i {
  d: path("M5.5 7.5V10a3 3 0 0 0 6 0V7.5m-9 14C2.5 18 5 16 8.5 16s6 2 6 5.5m2-8.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm.75 8.5c0-2.25.75-3.5 2-3.5s2.25 1.25 2.25 3.5");
}

</style>
