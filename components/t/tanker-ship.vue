<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ee2e1ubzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tanker-ship" /></template>
<style>
.ee2e1ubzu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 12.5a3 3 0 0 1 6 0Zm6.75 0a3 3 0 0 1 6 0Zm7 0V6.75a1 1 0 0 1 1-1H20a1 1 0 0 1 1 1v5.75Zm-14.75 0h18.5l-1.75 3.9a1.75 1.75 0 0 1-1.62 1.1H6.12a1.75 1.75 0 0 1-1.62-1.1Zm0 8.75c1.25 0 1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75");
}

</style>
