<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exljyccjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:transgender-symbol-sharp" /></template>
<style>
.exljyccjx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 8.5a3.75 3.75 0 1 1 0 7.5a3.75 3.75 0 1 1 0-7.5m0 7.5v5.25m-2.25-2.5h4.5m.4-9.15l5.6-5.35m-3.5 0h3.5v3.5M9.35 9.6l-5.6-5.35m3.5 0h-3.5v3.5M5.5 9L9 5.5");
}

</style>
