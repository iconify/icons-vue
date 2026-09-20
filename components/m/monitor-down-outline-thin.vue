<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jq9hovbrs"/><path class="m7p35uguv"/><path class="qdn88l2uv"/><path class="js960j4-t"/><path class="r5bn6xbek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:monitor-down-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jq9hovbrs {
  d: path("M14 4h5a3 3 0 0 1 3 3v7a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V7a3 3 0 0 1 3 -3h5");
}

.js960j4-t {
  d: path("M12 7.5v6");
}

.m7p35uguv {
  d: path("M12 17v3");
}

.qdn88l2uv {
  d: path("M7 20h10");
}

.r5bn6xbek {
  d: path("m9.5 11 2.5 2.5 2.5 -2.5");
}

</style>
