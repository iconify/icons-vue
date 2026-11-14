<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p1f-zdbgl"/><path class="fzuvp1brt"/><path class="smi5gzb5e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pit-in" /></template>
<style>
.fzuvp1brt {
  d: path("M4.5 2.5h5A3.5 3.5 0 0 1 13 6v10.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p1f-zdbgl {
  d: path("M10.5 10h5a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5h-5A3.5 3.5 0 0 1 7 18v-4.5a3.5 3.5 0 0 1 3.5-3.5");
}

.smi5gzb5e {
  d: path("M10.25 13.75L13 16.5l2.75-2.75");
}

</style>
