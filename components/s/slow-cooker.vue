<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rhhbx7x2y"/><rect class="nal5uibuo"/><path class="wpjigumbe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:slow-cooker" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nal5uibuo {
  width: 17.5px;
  height: 10.5px;
  x: 3.25px;
  y: 10.75px;
  rx: 3.5px;
}

.rhhbx7x2y {
  d: path("M10.5 2.75h3m-1.5 0v2.5m-7.5 3a7.5 3 0 0 1 15 0Z");
}

.wpjigumbe {
  d: path("M12 13.75a2 2 0 1 1 0 4a2 2 0 1 1 0-4");
}

</style>
