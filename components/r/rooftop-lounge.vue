<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9_chfv5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rooftop-lounge" /></template>
<style>
.e9_chfv5s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 16.5h17v5h-17Zm-1 0h19m-16-14h13l-6.5 7ZM12 5h.01M12 9.5v7m-3 0h6M7 19h.01M12 19h.01M17 19h.01");
}

</style>
