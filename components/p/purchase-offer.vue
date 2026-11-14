<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sydi58j_o"/><path class="cspwwh7ry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:purchase-offer" /></template>
<style>
.cspwwh7ry {
  d: path("m9.741 7.304l1.25-1.137a1.5 1.5 0 0 1 2.018 0l1.25 1.137a1.5 1.5 0 0 1 .491 1.11v.211a.875.875 0 0 1-.875.875h-3.75a.875.875 0 0 1-.875-.875v-.211a1.5 1.5 0 0 1 .491-1.11");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sydi58j_o {
  d: path("M10.25 2.5h3.5a4.75 4.75 0 0 1 4.75 4.75A4.75 4.75 0 0 1 13.75 12h-3.5A4.75 4.75 0 0 1 5.5 7.25a4.75 4.75 0 0 1 4.75-4.75M12 12v9.5");
}

</style>
