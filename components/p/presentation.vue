<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="jf3edpbej"/><path class="ijhqdybvf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:presentation" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ijhqdybvf {
  d: path("m7 11.75l3-3l2.5 2l4.5-4.5m-5 9.5v3m-3.5 2.5l3.5-2.5l3.5 2.5");
}

.jf3edpbej {
  width: 18.5px;
  height: 12.5px;
  x: 2.75px;
  y: 3.25px;
  rx: 2px;
}

</style>
