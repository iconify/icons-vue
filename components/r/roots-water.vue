<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dy1z1eb3f"/><path class="l1zujjbeg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:roots-water" /></template>
<style>
.dy1z1eb3f {
  d: path("M8 3v2.5L5.5 8v11a2 2 0 0 0 2 2h9a2 2 0 0 0 2-2V8L16 5.5V3M5.5 11h13");
}

.l1zujjbeg {
  d: path("M12 2.5V18m0-5q-3 1-3.5 4.5M12 13q3 1 3.5 4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
