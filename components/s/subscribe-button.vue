<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="sr_0fj4cl"/><path class="nk73kvqig"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:subscribe-button" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nk73kvqig {
  d: path("M7.25 10v4m-2-2h4m2-1.25h6.5m-6.5 2.5h4");
}

.sr_0fj4cl {
  width: 18.5px;
  height: 10px;
  x: 2.75px;
  y: 7px;
  rx: 5px;
}

</style>
