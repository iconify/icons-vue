<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njdvj3pls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wingsuit" /></template>
<style>
.njdvj3pls {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 4.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0M12 9l-9 .25v1.5Q8 13.5 8 21.5h1.5L12 18l2.5 3.5H16q0-8 5-10.75v-1.5Zm0 0v5.75");
}

</style>
