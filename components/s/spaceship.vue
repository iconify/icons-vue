<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lv6vid8px"/><circle class="qu-laubmi"/><path class="jx7p_kmzv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spaceship" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jx7p_kmzv {
  d: path("m6.34 10.6l-2.93 1.55q-.66.35 0 .7l2.93 1.55q.66.35.66-.4v-3q0-.75-.66-.4");
}

.lv6vid8px {
  d: path("M8.5 8.5h5c4 0 6.75 1.75 7.75 4c-1 2.25-3.75 4-7.75 4h-5A1.5 1.5 0 0 1 7 15v-5a1.5 1.5 0 0 1 1.5-1.5m-.84-.67L6.09 4.67Q5.75 4 6.5 4H8q.75 0 1.23.58l2.79 3.34q.48.58-.27.58h-3q-.75 0-1.09-.67m0 9.34l-1.57 3.16q-.34.67.41.67H8q.75 0 1.23-.58l2.79-3.34q.48-.58-.27-.58h-3q-.75 0-1.09.67");
}

.qu-laubmi {
  cx: 15.5px;
  cy: 12.5px;
  r: 1.5px;
}

</style>
