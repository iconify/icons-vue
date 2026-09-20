<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lp40tnqob"/><path class="a3eibhdgt"/><path class="z26gfvqcs"/><path class="s_9dtpvxy"/><path class="zl2kh1bxb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:travel-cover-duotone-bold" /></template>
<style>
.a3eibhdgt {
  d: path("M4.5 9.5a7.5 7.5 0 0 1 15 0");
}

.lp40tnqob {
  fill: currentColor;
  d: path("M8 15.5h8v5H8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s_9dtpvxy {
  d: path("M8 15.5h8v5H8Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.z26gfvqcs {
  d: path("M4.5 9.5h15");
}

.zl2kh1bxb {
  d: path("M10 15.5v-3h4v3");
}

</style>
