<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ot4uvhuas"/><path class="uefslbczy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:waypoint" /></template>
<style>
.ot4uvhuas {
  d: path("M15.5 16.5s-5.5-5-5.5-8a5.5 5.5 0 0 1 11 0c0 3-5.5 8-5.5 8ZM3 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.uefslbczy {
  d: path("M13.5 8.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM7 19h6q2.5 0 2.5-2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
