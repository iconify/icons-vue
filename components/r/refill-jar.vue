<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mqd4l9b2e"/><path class="rxuyrcbli"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:refill-jar" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mqd4l9b2e {
  d: path("M6.5 4.5V17A2.5 2.5 0 0 0 9 19.5h6a2.5 2.5 0 0 0 2.5-2.5V4.5m-12 0h13M12 8v7");
}

.rxuyrcbli {
  d: path("M9.5 12.5L12 15l2.5-2.5");
}

</style>
