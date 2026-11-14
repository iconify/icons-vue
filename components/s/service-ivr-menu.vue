<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgb48ob6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:service-ivr-menu" /></template>
<style>
.cgb48ob6t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.442 16.654C6.921 15.285 2.5 10.044 2.5 4.25c0-1 .75-1.75 1.75-1.75h2.5c.75 0 1 .5 1.25 1L8.75 6q0 1.125-.75 1.5l-1.25 1c1 2 2 3.25 4.25 4.25l.75-1.25q.75-.75 1.5-.75l2.75.75c.437 0 .874.382.977.978M15.25 15.25h.01m2.74 0h.01m2.74 0h.01M15.25 18h.01M18 18h.01m2.74 0h.01m-5.51 2.75h.01m2.74 0h.01m2.74 0h.01");
}

</style>
