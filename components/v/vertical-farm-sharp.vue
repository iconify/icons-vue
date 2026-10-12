<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_cm63b1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:vertical-farm-sharp" /></template>
<style>
.e_cm63b1s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 2.75v18.5m17-18.5v18.5m-17-13.5h17M3.5 14h17m-17 6.25h17m-14-12.5a2 3.25 0 0 1 4 0Zm7 0a2 3.25 0 0 1 4 0ZM6.5 14a2 3.25 0 0 1 4 0Zm7 0a2 3.25 0 0 1 4 0Zm-7 6.25a2 3.25 0 0 1 4 0Zm7 0a2 3.25 0 0 1 4 0Z");
}

</style>
