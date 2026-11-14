<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aq711fhir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wall-fountain" /></template>
<style>
.aq711fhir {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5H6v19H2.5ZM9 15h12.5A6.25 6.25 0 0 1 9 15ZM6 6h6.25q3 0 3 2.75m0 0V15m-2.75 0L11 12.75M18 15l1.5-2.25");
}

</style>
