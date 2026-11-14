<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wna3j0buj"/><path class="jl-laqb7z"/><path class="od-3zrwrv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tote-bag-printed" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jl-laqb7z {
  d: path("M6.5 10.5c0-8 7.5-8 7.5 0");
}

.od-3zrwrv {
  d: path("M10 10.5c0-8 7.5-8 7.5 0m-5.059 3.518l.088.205a1.5 1.5 0 0 0 1.235.897l.222.021a.48.48 0 0 1 .273.839l-.167.147a1.5 1.5 0 0 0-.472 1.452l.048.217a.48.48 0 0 1-.713.519l-.192-.114a1.5 1.5 0 0 0-1.526 0l-.192.114a.48.48 0 0 1-.713-.519l.048-.217a1.5 1.5 0 0 0-.472-1.452l-.167-.147a.48.48 0 0 1 .273-.839l.222-.021a1.5 1.5 0 0 0 1.235-.897l.088-.205a.48.48 0 0 1 .882 0");
}

.wna3j0buj {
  d: path("M5.416 10.5h13.168a1.75 1.75 0 0 1 1.743 1.908l-.682 7.5a1.75 1.75 0 0 1-1.743 1.592H6.098a1.75 1.75 0 0 1-1.743-1.592l-.682-7.5A1.75 1.75 0 0 1 5.416 10.5");
}

</style>
