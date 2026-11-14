<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddax3eb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:person-speaking" /></template>
<style>
.ddax3eb0y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 4.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM7 8v6.5M4 21l3-6.5l3 6.5m-6-9l3-3l3 3m5-9h4.5a2 2 0 0 1 2 2v3.5a2 2 0 0 1-2 2H16l-2.75 2.25V5A2 2 0 0 1 15 3Z");
}

</style>
