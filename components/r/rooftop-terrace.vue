<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vddv1_gor"/><path class="ft2tvac5v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rooftop-terrace" /></template>
<style>
.ft2tvac5v {
  d: path("M11.29 10.5h1.42a1.447 1.447 0 0 1 1.415 1.75l-.121.564A1.5 1.5 0 0 1 12.537 14h-1.074a1.5 1.5 0 0 1-1.467-1.186l-.121-.564a1.447 1.447 0 0 1 1.415-1.75m.71-2v2m-4-2a2 2 0 0 1 1-3a3 3 0 0 1 6 0a2 2 0 0 1 1 3Zm-1 8.25h.01m4.99 0h.01m4.99 0h.01M7 19.25h.01m4.99 0h.01m4.99 0h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vddv1_gor {
  d: path("M5.5 14h13a1.5 1.5 0 0 1 1.5 1.5V20a1.5 1.5 0 0 1-1.5 1.5h-13A1.5 1.5 0 0 1 4 20v-4.5A1.5 1.5 0 0 1 5.5 14m-3 0h19");
}

</style>
