<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3axw2vcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spiderweb" /></template>
<style>
.j3axw2vcv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12V2.75M12 12l6.54-6.54M12 12h9.25M12 12l6.54 6.54M12 12v9.25M12 12l-6.54 6.54M12 12H2.75M12 12L5.46 5.46M12 5.5q2.04 1.58 4.6 1.9m0 0q.32 2.56 1.9 4.6m0 0q-1.58 2.04-1.9 4.6m0 0q-2.56.32-4.6 1.9m0 0q-2.04-1.58-4.6-1.9m0 0q-.32-2.56-1.9-4.6m0 0q1.58-2.04 1.9-4.6m0 0q2.56-.32 4.6-1.9m0 3.25q.99.85 2.3.95m0 0q.1 1.31.95 2.3m0 0q-.85.99-.95 2.3m0 0q-1.31.1-2.3.95m0 0q-.99-.85-2.3-.95m0 0q-.1-1.31-.95-2.3m0 0q.85-.99.95-2.3m0 0q1.31-.1 2.3-.95");
}

</style>
