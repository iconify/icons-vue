<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lhjoqfiio"/><rect class="qvkbozqwr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:quill" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lhjoqfiio {
  d: path("M20.75 3.25c-5.5 0-10 3.75-10.5 9.75l.75.75c6-.5 9.75-5 9.75-10.5m-9 9L16.5 7.5m-8.25 8.25l2.25-2.25");
}

.qvkbozqwr {
  width: 8.5px;
  height: 5.5px;
  x: 3.25px;
  y: 15.75px;
  rx: 1.5px;
}

</style>
