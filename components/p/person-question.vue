<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apc3i0b5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:person-question" /></template>
<style>
.apc3i0b5j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 4.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM7 8v6.5M4 21l3-6.5l3 6.5m-6.5-9L7 9l3.5 3m4-5.75c0-1.55 1.25-2.75 3-2.75s3 1.2 3 2.75c0 2.25-3 2.5-3 4.75m0 3.5h.01");
}

</style>
