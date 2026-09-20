<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tfnum6bjl"/><path class="z55just5o"/><path class="b4373m80b"/><path class="ryzx2-jfe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:subquestion-outline-bold" /></template>
<style>
.b4373m80b {
  d: path("M14.5 13.5A2.5 2.5 0 1 1 17 16");
}

.ryzx2-jfe {
  d: path("M16 19.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tfnum6bjl {
  d: path("M4 7a4 4 0 1 1 4 4");
}

.z55just5o {
  d: path("M7 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
