<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ksica-_xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:papyrus-plant" /></template>
<style>
.ksica-_xl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.5V10m0 0L3.5 7m8.5 3L6.5 3.5M12 10V2m0 8l5.5-6.5M12 10l8.5-3M7 21.5h10");
}

</style>
