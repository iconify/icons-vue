<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t_y4gcbyc"/><path class="mnga3lbbk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:water-garden-bowl" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mnga3lbbk {
  d: path("M7.5 15q2.25-1.25 4.5 0t4.5 0M12 11V6m0 1.5c0-2 1.75-3.5 4.25-3.5c0 2-1.75 3.5-4.25 3.5m0 1C9.5 8.5 7.75 7 7.75 5C10.25 5 12 6.5 12 8.5");
}

.t_y4gcbyc {
  d: path("M3 11h18c0 5.25-4 9-9 9s-9-3.75-9-9");
}

</style>
