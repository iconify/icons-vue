<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="km8lmlbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:travel-adapter" /></template>
<style>
.km8lmlbdz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.875 8h4.25a4.375 4.375 0 0 1 4.375 4.375v.25A4.375 4.375 0 0 1 14.125 17h-4.25A4.375 4.375 0 0 1 5.5 12.625v-.25A4.375 4.375 0 0 1 9.875 8M9.5 8V4m5 4V4M12 17v4");
}

</style>
