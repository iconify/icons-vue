<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="iezljm-7a"/><path class="xyj-l9cjp"/><path class="y-a5g9b6x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:market-closed-duotone-bold" /></template>
<style>
.iezljm-7a {
  fill: currentColor;
  d: path("M12 3a6.5 6.5 0 1 0 6.5 9.5A5.5 5.5 0 0 1 12 3");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xyj-l9cjp {
  d: path("M3 18h18");
}

.y-a5g9b6x {
  d: path("M12 3a6.5 6.5 0 1 0 6.5 9.5A5.5 5.5 0 0 1 12 3");
}

</style>
