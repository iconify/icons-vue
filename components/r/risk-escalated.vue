<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl4fyt4dx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:risk-escalated" /></template>
<style>
.bl4fyt4dx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.558 18.5H2.5l9-16l5.393 9.587M11.5 8.5V12m0 3h.01M18 21v-6m-2.5 2.5L18 15l2.5 2.5");
}

</style>
