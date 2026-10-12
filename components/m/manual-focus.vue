<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="fp15l5b4i"/><path class="g3n9c8l9l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:manual-focus" /></template>
<style>
.fp15l5b4i {
  width: 13px;
  height: 10.5px;
  x: 2.75px;
  y: 6.75px;
  rx: 2px;
}

.g3n9c8l9l {
  d: path("M7 6.75v10.5m2.75-10.5v10.5m2.75-10.5v10.5m5.75-9.75a6 6 0 0 1 0 9m2.49-.2l-2.49.2l.51-2.45");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
