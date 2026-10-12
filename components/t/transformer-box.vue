<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ac32awbtf"/><path class="sifgi0b5q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:transformer-box" /></template>
<style>
.ac32awbtf {
  width: 17.5px;
  height: 15.25px;
  x: 3.25px;
  y: 6px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sifgi0b5q {
  d: path("M8 6V2.75M16 6V2.75M9.25 9.5a1.5 1.5 0 0 1 0 3a1.5 1.5 0 0 1 0 3a1.5 1.5 0 0 1 0 3m5.5-9a1.5 1.5 0 0 0 0 3a1.5 1.5 0 0 0 0 3a1.5 1.5 0 0 0 0 3");
}

</style>
