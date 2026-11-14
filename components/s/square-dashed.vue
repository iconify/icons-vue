<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-3k6jyyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:square-dashed" /></template>
<style>
.z-3k6jyyk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 6v-.5a2 2 0 0 1 2-2H6m12 0h.5a2 2 0 0 1 2 2V6m0 12v.5a2 2 0 0 1-2 2H18m-12 0h-.5a2 2 0 0 1-2-2V18M9 3.5h1.5m3 0H15m-6 17h1.5m3 0H15M3.5 9v1.5m0 3V15m17-6v1.5m0 3V15");
}

</style>
