<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k5tz39b_s"/><path class="et9l4bb9u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pressure-gauge-dive" /></template>
<style>
.et9l4bb9u {
  d: path("M11 17.5V19c0 1.75 2 2.5 5 2.5h5M7.818 13.182a4.5 4.5 0 0 1 0-6.364");
}

.k5tz39b_s {
  d: path("M3.5 10a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0Zm7.5 0l3.5-3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
