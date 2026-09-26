<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="nl6i3qb2f"/><path class="ess6f3oak"/><path class="q_i5o_bfs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-right-close-dashed-sharp-duotone" /></template>
<style>
.ess6f3oak {
  d: path("M7 3L3 3L3 7M3 17L3 21L7 21M9 3L12 3M9 21L12 21M3 9.5L3 14.5");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nl6i3qb2f {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 2L21 2C21.5523 2 22 2.4477 22 3L22 21C22 21.5523 21.5523 22 21 22L15 22C14.4477 22 14 21.5523 14 21L14 3C14 2.4477 14.4477 2 15 2Z");
  stroke: none;
}

.q_i5o_bfs {
  d: path("M7.7071 8.7071L11 12L7.7071 15.2929");
}

</style>
