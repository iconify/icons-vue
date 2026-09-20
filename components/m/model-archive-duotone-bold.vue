<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="a1g1t6b8b"/><path class="ulgy3xb-n"/><path class="o3xv3zb-q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:model-archive-duotone-bold" /></template>
<style>
.a1g1t6b8b {
  fill: currentColor;
  d: path("m12 3 5 5 -5 5 -5 -5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.o3xv3zb-q {
  d: path("M3 15v6h18v-6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ulgy3xb-n {
  d: path("m12 3 5 5 -5 5 -5 -5Z");
}

</style>
