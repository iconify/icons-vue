<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jwjajfi6y"/><path class="ey7qyccbu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rock-pile" /></template>
<style>
.ey7qyccbu {
  d: path("m8 11l4 1.5l5.5-4m-5.5 4l.75 7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jwjajfi6y {
  d: path("m2.5 19.5l1.5-6L8 11l2-4l4.5-1.5l3 3l3 3.5l1 7.5Z");
}

</style>
