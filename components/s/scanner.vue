<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="cb5jl7bbd"/><path class="dk0px4bmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:scanner" /></template>
<style>
.cb5jl7bbd {
  width: 18.5px;
  height: 9px;
  x: 2.75px;
  y: 11.25px;
  rx: 2.5px;
}

.dk0px4bmn {
  d: path("M4.25 11.25L15.75 3m-9.5 12h11.5m-2.25 2.5h2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
