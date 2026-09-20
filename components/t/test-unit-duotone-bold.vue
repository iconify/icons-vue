<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="l1szmbb7n"/><path class="eh4bvfj1i"/><path class="uwjz-dbef"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:test-unit-duotone-bold" /></template>
<style>
.eh4bvfj1i {
  d: path("M6 6a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

.l1szmbb7n {
  fill: currentColor;
  d: path("M6 6a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uwjz-dbef {
  d: path("m9 12 2 2 4 -4");
}

</style>
