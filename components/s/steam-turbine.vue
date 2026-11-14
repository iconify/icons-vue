<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tzvowjbyq"/><path class="q-36szbpa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:steam-turbine" /></template>
<style>
.q-36szbpa {
  d: path("M12.75 10.5q2.536.317 3.665 2.543M11.5 12.5q1.5 3.5-1.75 6m-.25-6Q7 15.5 3.25 14m5-3.5Q4.5 10 4 6m5.5 2.5Q8 5 11.25 2.5m.25 6q2.5-3 6.25-1.5m-1.5 14.5H20a2 2 0 0 0 0-4a2.75 2.75 0 0 0-5.25.5a2 2 0 0 0 1.5 3.5Z");
}

.tzvowjbyq {
  d: path("M8.25 10.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
