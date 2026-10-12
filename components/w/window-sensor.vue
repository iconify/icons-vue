<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ddwl7oyiu"/><path class="fsz9ogb0w"/><rect class="rhgf94b9y"/><path class="v1ssl2x3h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:window-sensor" /></template>
<style>
.ddwl7oyiu {
  width: 12.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 1.5px;
}

.fsz9ogb0w {
  d: path("M9 2.75v18.5M2.75 12h12.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rhgf94b9y {
  width: 3.25px;
  height: 6px;
  x: 18px;
  y: 6.75px;
  rx: 1.25px;
}

.v1ssl2x3h {
  d: path("M18 16.25h3.25");
}

</style>
