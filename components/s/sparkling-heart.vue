<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8csm7uef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sparkling-heart" /></template>
<style>
.o8csm7uef {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 20.79c-.3 0-.6-.11-.83-.3c-2.47-2.06-5.73-4.69-5.73-8.21c0-2.03 1.53-3.68 3.49-3.68c1.2 0 2.25.6 3.07 1.65c.82-1.05 1.88-1.65 3.08-1.65c1.95 0 3.49 1.65 3.49 3.68c0 3.53-3.26 6.15-5.74 8.21c-.22.19-.52.3-.83.3m7.5-18.04q.33 2.42 2.75 2.75q-2.42.33-2.75 2.75Q17.42 5.83 15 5.5q2.42-.33 2.75-2.75");
}

</style>
