<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d837u3b_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:two-person-lift" /></template>
<style>
.d837u3b_x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 5.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm12 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM6 8v6l-2 5m2-5l2 5M18 8v6l-2 5m2-5l2 5M8 9h8v5H8Z");
}

</style>
