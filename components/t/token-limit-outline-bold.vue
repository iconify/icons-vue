<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lokgnabwi"/><path class="i4kf51esh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:token-limit-outline-bold" /></template>
<style>
.i4kf51esh {
  d: path("M19 5v14");
}

.lokgnabwi {
  d: path("M3 12a3 3 0 0 1 3 -3h7a3 3 0 0 1 3 3 3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
