<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="kxq9ww4ym"/><path class="nme2a4b2w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:periodic-element" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kxq9ww4ym {
  width: 16.5px;
  height: 16.5px;
  x: 3.75px;
  y: 3.75px;
  rx: 2.5px;
}

.nme2a4b2w {
  d: path("M7.25 6.75V8m2.25 2.5V17m5-6.5V17m-5-3.25h5");
}

</style>
