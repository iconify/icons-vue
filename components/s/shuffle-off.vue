<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3gbtqcju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shuffle-off" /></template>
<style>
.g3gbtqcju {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 17.25h2.5c1.3 0 2.5-.65 3.25-1.7l4.98-7.1a3.95 3.95 0 0 1 3.27-1.7h2.5M17.5 4l2.75 2.75L17.5 9.5M3.75 6.75h2.5c1.3 0 2.5.65 3.25 1.7l.75 1.05m3.5 5l.75 1.05c.75 1.05 1.95 1.7 3.25 1.7h2.5M17.5 14.5l2.75 2.75L17.5 20");
}

</style>
