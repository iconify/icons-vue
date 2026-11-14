<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="st-yp7bjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wing-corkscrew" /></template>
<style>
.st-yp7bjb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 7h4v9h-4ZM9 3h6m-3 0v4m-2 2L5.5 5M14 9l4.5-4M12 16l1.5 1.25l-3 1.5l3 1.5L12 21");
}

</style>
