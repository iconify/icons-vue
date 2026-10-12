<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owm7c4bql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pressure-washer-sharp" /></template>
<style>
.owm7c4bql {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 4.75H3.5v4.5H5l.09 1.25l.32 4.25L5.5 16h3.25l-.09-1.25l-.32-4.25l-.09-1.25H9v-4.5zM9 7h7.25m-9 9v4.25h10m1.5-15L21 3.5M19 7h2.25m-2.5 1.75L21 10.5");
}

</style>
