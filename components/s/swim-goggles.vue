<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o03evcc8v"/><path class="b1b3qo53v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:swim-goggles" /></template>
<style>
.b1b3qo53v {
  d: path("M3.75 14.5c0-9.5 16.5-9.5 16.5 0");
}

.o03evcc8v {
  d: path("M3.75 14.5a3.5 3 0 1 0 7 0a3.5 3 0 1 0-7 0Zm9.5 0a3.5 3 0 1 0 7 0a3.5 3 0 1 0-7 0Zm-2.5 0h2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
