<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8ym1qb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:training-cone" /></template>
<style>
.p8ym1qb3o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 17c0-1.5 3-2.5 5.5-3l1.75-6h3.5l1.75 6c2.5.5 5.5 1.5 5.5 3s-4 2.5-9 2.5s-9-1-9-2.5m6.25-5.5h5.5");
}

</style>
