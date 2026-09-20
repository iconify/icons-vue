<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="d61-nrbot"/><path class="tbr5-0t2d"/><path class="af8xzachr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:nut-allergy-duotone-bold" /></template>
<style>
.af8xzachr {
  d: path("M6 19 18 7");
}

.d61-nrbot {
  fill: currentColor;
  d: path("M12 3c4 3 6 7 6 11a6 6 0 0 1 -12 0c0 -4 2 -8 6 -11");
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

.tbr5-0t2d {
  d: path("M12 3c4 3 6 7 6 11a6 6 0 0 1 -12 0c0 -4 2 -8 6 -11");
}

</style>
