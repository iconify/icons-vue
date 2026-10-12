<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="sqztt6b8y"/><path class="c2zkhdgia"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rain-gauge-sharp" /></template>
<style>
.c2zkhdgia {
  d: path("M7.5 15.5q2.25-2 4.5 0t4.5 0");
}

.sqztt6b8y {
  d: path("M5.1 2.75h14.4l-.37.47l-2.26 2.81l-.37.47h-9l-.37-.47l-2.26-2.81l-.37-.47zM7.5 6.5h9v14.75h-9zm0 4.25h3");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
