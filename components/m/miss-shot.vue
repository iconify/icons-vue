<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pr1e_o6tc"/><path class="k_00gub7s"/><path class="exogbkivh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:miss-shot" /></template>
<style>
.exogbkivh {
  d: path("M14 3.5q3.5 3.5 0 7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k_00gub7s {
  d: path("m3 13.5l2 7L7.5 17l2.5 3.5l2-7m.5-6.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0m0 0h9");
}

.pr1e_o6tc {
  d: path("M2.5 13a5 1.5 0 1 0 10 0a5 1.5 0 1 0-10 0");
}

</style>
