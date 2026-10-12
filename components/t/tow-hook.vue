<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x7g8l4apy"/><rect class="y7gj8abnh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tow-hook" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x7g8l4apy {
  d: path("M12 17v-5.5a4 4 0 1 1 3.46-6");
}

.y7gj8abnh {
  width: 12px;
  height: 4.25px;
  x: 6px;
  y: 17px;
  rx: 1.25px;
}

</style>
