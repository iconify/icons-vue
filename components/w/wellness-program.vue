<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5n83iazh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wellness-program" /></template>
<style>
.s5n83iazh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 4.5C14.75 7 14.75 12 12 15c-2.75-3-2.75-8 0-10.5m0 13c-5 0-8.5-3-9-8c3 .25 5.5 1.5 6.75 3.25M12 17.5c5 0 8.5-3 9-8c-3 .25-5.5 1.5-6.75 3.25");
}

</style>
