<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="teoo8vbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:map-grid-sharp" /></template>
<style>
.teoo8vbon {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.4 5.75l3.45-1.5L9 3.75l1.15.48l3.7 1.54l1.15.48l1.15-.5l3.45-1.5l1.15-.5v14l-1.15.5l-3.45 1.5l-1.15.5l-1.15-.48l-3.7-1.54L9 17.75l-1.15.5l-3.45 1.5l-1.15.5v-14zm4.6-2v14M3.25 12h17.5");
}

</style>
