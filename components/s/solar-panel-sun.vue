<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvq-5lj9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:solar-panel-sun" /></template>
<style>
.dvq-5lj9j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.309 12.5h11.352a1.75 1.75 0 0 1 1.679 2.244l-1.471 5A1.75 1.75 0 0 1 17.191 21H5.839a1.75 1.75 0 0 1-1.679-2.244l1.471-5A1.75 1.75 0 0 1 7.309 12.5M4.75 16.75h15M13.5 12.5L11 21M9.75 7.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M12 3.75V2M8.25 7.5H6.5m9.25 0h1.75M9.25 4.75L8 3.5m6.75 1.25L16 3.5");
}

</style>
