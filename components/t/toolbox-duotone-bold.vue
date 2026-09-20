<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qb7dqkbxu"/><path class="oy6b_1b_a"/><path class="ltriwmbuu"/><path class="yngda3bvc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:toolbox-duotone-bold" /></template>
<style>
.ltriwmbuu {
  d: path("M8 10a4 4 0 0 1 8 0");
}

.oy6b_1b_a {
  d: path("M3 20V10h18v10Z");
}

.qb7dqkbxu {
  fill: currentColor;
  d: path("M3 20V10h18v10Z");
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

.yngda3bvc {
  d: path("M3 15h18");
}

</style>
