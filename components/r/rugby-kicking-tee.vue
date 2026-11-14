<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aoemi0bik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rugby-kicking-tee" /></template>
<style>
.aoemi0bik {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5A7.5 7.5 0 0 1 12 16a7.5 7.5 0 0 1 0-13.5Zm-5 19h10L14.5 16h-5Zm5-15.25v6m-1.25-4.5h2.5m-2.5 3h2.5");
}

</style>
