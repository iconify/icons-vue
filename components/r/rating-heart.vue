<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1tqbuekr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rating-heart" /></template>
<style>
.o1tqbuekr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 11S8.25 8.75 8.25 6.5c0-1.25.75-2 2-2c.75 0 1.25.25 1.75 1c.5-.75 1-1 1.75-1c1.25 0 2 .75 2 2C15.75 8.75 12 11 12 11m-5.5 9.25S2.75 18 2.75 15.75c0-1.25.75-2 2-2c.75 0 1.25.25 1.75 1c.5-.75 1-1 1.75-1c1.25 0 2 .75 2 2c0 2.25-3.75 4.5-3.75 4.5m11 0s-3.75-2.25-3.75-4.5c0-1.25.75-2 2-2c.75 0 1.25.25 1.75 1c.5-.75 1-1 1.75-1c1.25 0 2 .75 2 2c0 2.25-3.75 4.5-3.75 4.5");
}

</style>
