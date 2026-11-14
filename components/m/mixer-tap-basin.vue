<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3arlgbgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mixer-tap-basin" /></template>
<style>
.q3arlgbgl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 15.5h18c0 3-4 5-9 5s-9-2-9-5Zm2.5 0V7H9v8.5m0-7h5.5A1.5 1.5 0 0 1 16 10M7.25 7l3.5-3.5M16 12.75h.01");
}

</style>
