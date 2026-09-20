<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c3k06p-yv"/><path class="abchdfb3i"/><path class="uicwdzbry"/><path class="yl8oldl7l"/><path class="owdk3hf1a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tempo-duotone-bold" /></template>
<style>
.abchdfb3i {
  d: path("M4 17a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.c3k06p-yv {
  fill: currentColor;
  d: path("M4 17a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.owdk3hf1a {
  d: path("m18 8 4 4 -4 4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uicwdzbry {
  d: path("M10 17V6");
}

.yl8oldl7l {
  d: path("m13 8 4 4 -4 4");
}

</style>
