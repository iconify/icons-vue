<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ky7fjq4zo"/><path class="n939_wb7j"/><path class="vop2ak6bn"/><path class="kr13ht3hf"/><path class="tfnum6bjl"/><path class="z55just5o"/><path class="b4373m80b"/><path class="ryzx2-jfe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:subquestion-duotone-bold" /></template>
<style>
.b4373m80b {
  d: path("M14.5 13.5A2.5 2.5 0 1 1 17 16");
}

.kr13ht3hf {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14.5 13.5A2.5 2.5 0 1 1 17 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ky7fjq4zo {
  fill: currentColor;
  d: path("M7 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.n939_wb7j {
  fill: currentColor;
  d: path("M16 19.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
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

.vop2ak6bn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 7a4 4 0 1 1 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z55just5o {
  d: path("M7 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
