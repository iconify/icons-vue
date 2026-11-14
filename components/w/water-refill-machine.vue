<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="awq7emboz"/><path class="wwj5jbczl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:water-refill-machine" /></template>
<style>
.awq7emboz {
  d: path("M6 2.5h4A3.5 3.5 0 0 1 13.5 6v12a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 18V6A3.5 3.5 0 0 1 6 2.5M13.5 8h5.25v2.5m-2.5 11v-6l1.25-2h2.75l1.25 2v6Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wwj5jbczl {
  d: path("m8 7l1.75 3.25a2 2 0 1 1-3.5 0Z");
}

</style>
