<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj4wdzbmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:motorway-interchange" /></template>
<style>
.jj4wdzbmx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v19M2.5 12h6.75m5.5 0h6.75M12 8.5a3.5 3.5 0 1 1 3.5 3.5m-7 0A3.5 3.5 0 1 1 12 8.5m3.5 3.5a3.5 3.5 0 1 1-3.5 3.5m0 0A3.5 3.5 0 1 1 8.5 12");
}

</style>
