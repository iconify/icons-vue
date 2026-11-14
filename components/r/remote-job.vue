<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c9zfzjbvv"/><path class="vt1zdwbih"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:remote-job" /></template>
<style>
.c9zfzjbvv {
  d: path("M5.125 3h7.75A2.625 2.625 0 0 1 15.5 5.625v3.25a2.625 2.625 0 0 1-2.625 2.625h-7.75A2.625 2.625 0 0 1 2.5 8.875v-3.25A2.625 2.625 0 0 1 5.125 3M2 14h11.5m1 3.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vt1zdwbih {
  d: path("M16.5 17.5a1.5 3.5 0 1 0 3 0a1.5 3.5 0 1 0-3 0m-2 0h7");
}

</style>
