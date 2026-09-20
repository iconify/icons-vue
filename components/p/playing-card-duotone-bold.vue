<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="x6guzjh7r"/><path class="xea12qb_o"/><path class="j8arz0w3t"/><path class="r-kal0b4m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:playing-card-duotone-bold" /></template>
<style>
.j8arz0w3t {
  d: path("M6 5a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

.r-kal0b4m {
  d: path("M12 17c-2.5 -2 -6 -5 -4.5 -8 1 -2 3 -1.5 4.5 0.5 1.5 -2 3.5 -2.5 4.5 -0.5 1.5 3 -2 6 -4.5 8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.x6guzjh7r {
  fill: currentColor;
  d: path("M6 5a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xea12qb_o {
  fill: currentColor;
  d: path("M12 17c-2.5 -2 -6 -5 -4.5 -8 1 -2 3 -1.5 4.5 0.5 1.5 -2 3.5 -2.5 4.5 -0.5 1.5 3 -2 6 -4.5 8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
