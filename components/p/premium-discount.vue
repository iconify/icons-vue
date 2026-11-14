<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnvk0evfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:premium-discount" /></template>
<style>
.pnvk0evfl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 10.913V6.125A2.625 2.625 0 0 1 6.125 3.5h4.788a2.63 2.63 0 0 1 1.856.769l5.875 5.875a2.625 2.625 0 0 1 0 3.712l-4.788 4.788a2.625 2.625 0 0 1-3.712 0l-5.875-5.875a2.63 2.63 0 0 1-.769-1.856M8 8h.01m6.49 2.5l-4 4M11 11h.01M14 14h.01");
}

</style>
