<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rk6vfs05v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:seed-germination" /></template>
<style>
.rk6vfs05v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 18.5a3 2 0 1 0 6 0a3 2 0 1 0-6 0ZM2.5 14h19M12 16.5v-8m0 2c-3 0-5.25-2-5.25-4.75c3 0 5.25 2 5.25 4.75Zm0-2c0-2.75 2.25-4.75 5.25-4.75C17.25 6.5 15 8.5 12 8.5Z");
}

</style>
