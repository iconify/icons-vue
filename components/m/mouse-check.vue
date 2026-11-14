<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rz27lryrq"/><path class="is9z-p8nm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mouse-check" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.is9z-p8nm {
  d: path("m9.75 14.5l1.5 1.5l3-3");
}

.rz27lryrq {
  d: path("M12 3za5.5 5.5 0 0 1 5.5 5.5v7A5.5 5.5 0 0 1 12 21a5.5 5.5 0 0 1-5.5-5.5v-7A5.5 5.5 0 0 1 12 3m0 3.5v3");
}

</style>
