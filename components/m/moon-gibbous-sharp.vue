<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-o0mlb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:moon-gibbous-sharp" /></template>
<style>
.p-o0mlb6p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75a9.25 9.25 0 0 1 0 18.5a4.75 9.25 0 0 1 0-18.5ZM6.05 4.91a9.25 9.25 0 0 0 0 14.18");
}

</style>
