<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="um53i40nw"/><path class="eki57g2sa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mouse-scroll" /></template>
<style>
.eki57g2sa {
  d: path("M12 6.75v3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.um53i40nw {
  width: 11.5px;
  height: 18.5px;
  x: 6.25px;
  y: 2.75px;
  rx: 5.75px;
}

</style>
