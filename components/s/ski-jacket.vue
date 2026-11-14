<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_x0pqisg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ski-jacket" /></template>
<style>
.u_x0pqisg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 6.5L4.5 8l-2 10H6l1-4.5V21h10v-7.5l1 4.5h3.5l-2-10l-4-1.5a3.5 3.5 0 0 0-7 0ZM12 10v11");
}

</style>
