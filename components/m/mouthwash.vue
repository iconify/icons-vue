<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="dcdfcabho"/><path class="b_rytqb2i"/><path class="w9fye5bvt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mouthwash" /></template>
<style>
.b_rytqb2i {
  d: path("M10.5 6.25h3q1.25 0 1.25 1.13q0 1.12.95 1.93l1.6 1.38q.95.81.95 2.06V20q0 1.25-1.25 1.25H7q-1.25 0-1.25-1.25v-7.25q0-1.25.95-2.06l1.6-1.38q.95-.81.95-1.93q0-1.13 1.25-1.13");
}

.dcdfcabho {
  width: 6.5px;
  height: 3.5px;
  x: 8.75px;
  y: 2.75px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w9fye5bvt {
  d: path("M5.75 15.5c2-1 4.25-1 6.25 0s4.25 1 6.25 0");
}

</style>
