<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tpp-v41yj"/><path class="o6mud2b1x"/><path class="b8renebth"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:samba-drum" /></template>
<style>
.b8renebth {
  d: path("m4 11.5l3.5 5.75L11 11.5l3.5 5.75L18 11.5M13 5l8.5-2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o6mud2b1x {
  d: path("M4 6v12.5a7 2.5 0 0 0 14 0V6");
}

.tpp-v41yj {
  d: path("M4 6a7 2.5 0 1 0 14 0A7 2.5 0 1 0 4 6");
}

</style>
