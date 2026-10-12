<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tp_9c6byd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:plane-star" /></template>
<style>
.tp_9c6byd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75c1 0 1.75.8 1.75 1.75v4.75L20.1 13a.75.75 0 0 1 .4.65v.95a.5.5 0 0 1-.65.48l-6.1-1.83v4.25l1.85 1.4a.75.75 0 0 1 .3.6v.8a.5.5 0 0 1-.66.47L12 19.75l-3.24 1.02a.5.5 0 0 1-.66-.47v-.8a.75.75 0 0 1 .3-.6l1.85-1.4v-4.25l-6.1 1.83a.5.5 0 0 1-.65-.48v-.95a.75.75 0 0 1 .4-.65l6.35-3.75V4.5c0-.95.75-1.75 1.75-1.75");
}

</style>
