<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jt6fpykbb"/><path class="nw66r3bzx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:woodworking" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jt6fpykbb {
  d: path("M5 14h14a2.5 2.5 0 0 1 2.5 2.5A2.5 2.5 0 0 1 19 19H5a2.5 2.5 0 0 1-2.5-2.5A2.5 2.5 0 0 1 5 14m-1.5 0L5 8.5h3.5L10 14m8.5 0v-1.75a1.5 1.5 0 0 1 3 0V14");
}

.nw66r3bzx {
  d: path("M12.5 14c0-6.5 3.5-10 6-9c2 .75 1 4-1.5 3");
}

</style>
