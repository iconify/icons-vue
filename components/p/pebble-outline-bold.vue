<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pj9q08bqv"/><path class="vtk0-_bov"/><path class="pe31e6bgt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pebble-outline-bold" /></template>
<style>
.pe31e6bgt {
  d: path("M7.5 17a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

.pj9q08bqv {
  d: path("M3 9a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vtk0-_bov {
  d: path("M12.5 8a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

</style>
