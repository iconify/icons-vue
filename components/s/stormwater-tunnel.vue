<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o2k1jl29t"/><path class="kv23z-bca"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stormwater-tunnel" /></template>
<style>
.kv23z-bca {
  d: path("M7 16.5v-3a5 5 0 0 1 10 0v3M3 19.75q2-1.5 4 0t4 0t4 0t4 0q1-.75 2 0");
}

.o2k1jl29t {
  d: path("M2.5 16.5V12a9.5 9.5 0 0 1 19 0v4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
