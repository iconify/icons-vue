<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrmm5bw4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:yogurt-sharp" /></template>
<style>
.lrmm5bw4s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 11h15.5l-1.5 8.75l-.214 1.268L16.75 21h-9.5l-1.286.018l-.214-1.268Zm.6 3.5h14.3M11.5 11c.25-3 2.25-5.25 5.25-5.75l1.841-.253l-.141 1.853l-.2 4.15Z");
}

</style>
