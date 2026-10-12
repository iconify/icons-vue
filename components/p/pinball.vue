<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j-8o11l4j"/><circle class="z2o0ujiuj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pinball" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j-8o11l4j {
  d: path("m4.24 12.84l1.02-.18q.99-.16 1.64.6l2.95 3.48q.65.76.15 1.39q-.5.62-1.39.17l-3.72-1.85Q4 16 3.76 15.03l-.27-1.06q-.24-.97.75-1.13m15.52 0l-1.02-.18q-.99-.16-1.64.6l-2.95 3.48q-.65.76-.15 1.39q.5.62 1.39.17l3.72-1.85q.89-.45 1.13-1.42l.27-1.06q.24-.97-.75-1.13");
}

.z2o0ujiuj {
  cx: 12px;
  cy: 7px;
  r: 3px;
}

</style>
