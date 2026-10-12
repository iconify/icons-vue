<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pdplahujw"/><circle class="rupz06b6d"/><path class="ng89jh3vs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:plough" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ng89jh3vs {
  d: path("M9 13.5h7l3 4a1 1 0 0 1-.8 1.6H11a2 2 0 0 1-2-2Z");
}

.pdplahujw {
  d: path("M21.25 3.25L17 9.5m-14.25 0H17m-4 0v4m-8-4v6");
}

.rupz06b6d {
  cx: 5px;
  cy: 17.5px;
  r: 2px;
}

</style>
