<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3e0t6b7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:triangle-pose" /></template>
<style>
.c3e0t6b7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 4.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM12 9v4.5M4.5 21l7.5-7.5l7.5 7.5M12 11.5L18.5 5");
}

</style>
