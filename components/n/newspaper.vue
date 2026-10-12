<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="evev8i0wg"/><path class="oors38uja"/><rect class="ai7d7gbak"/><path class="fiagbzb0w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:newspaper" /></template>
<style>
.ai7d7gbak {
  width: 5.5px;
  height: 4.5px;
  x: 9.5px;
  y: 7px;
  rx: 1px;
}

.evev8i0wg {
  width: 15px;
  height: 16.5px;
  x: 6.25px;
  y: 3.75px;
  rx: 2.5px;
}

.fiagbzb0w {
  d: path("M9.5 14.75h8.25M9.5 17.5H15");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oors38uja {
  d: path("M6.25 20.25h-1.5a2 2 0 0 1-2-2v-9.5h3.5");
}

</style>
