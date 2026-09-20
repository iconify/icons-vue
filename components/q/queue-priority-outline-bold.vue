<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zaji3hbsg"/><path class="yuybrcb9z"/><path class="wa8tqsbro"/><path class="y0x-x3b-m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:queue-priority-outline-bold" /></template>
<style>
.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wa8tqsbro {
  d: path("M17.5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.y0x-x3b-m {
  d: path("M2 18h19");
}

.yuybrcb9z {
  d: path("M12 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.zaji3hbsg {
  d: path("M5.5 8.5 9 12l-3.5 3.5L2 12Z");
}

</style>
