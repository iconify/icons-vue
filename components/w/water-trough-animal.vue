<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c_2eo14_v"/><path class="bl0sl_blu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:water-trough-animal" /></template>
<style>
.bl0sl_blu {
  d: path("M3.75 9q2-1 4 0t4 0t4 0t4.5 0m-4 11a2.25 1.5 0 1 0 4.5 0a2.25 1.5 0 1 0-4.5 0Zm-.5-3.5h.01m2.74-1.25h.01m2.74 1.25h.01");
}

.c_2eo14_v {
  d: path("m2.5 5l2 8h11.154m3.98-.537L21.5 5m-15 8v4m7-4v.7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
