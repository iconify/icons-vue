<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="exmm83u7y"/><path class="kkm03rbxe"/><path class="sb40gqbga"/><path class="bos0j4biy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:staircase-duotone-bold" /></template>
<style>
.bos0j4biy {
  d: path("M3 21h18");
}

.exmm83u7y {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 21v-4h5v-4h5V9h5V5h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kkm03rbxe {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 21h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sb40gqbga {
  d: path("M3 21v-4h5v-4h5V9h5V5h3");
}

</style>
