<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eghlwib7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pos-no-sale" /></template>
<style>
.eghlwib7d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5h10V9H3ZM8 9v1.5m5.3 4H4v-4h16v1.4m-6.7 9.6H2.5v-4h10m-8.5-3l-1.5 3m5-5h.01m4.49 0h.01m-5.51 7h4m4.75-1.5a2.75 3.75 0 1 0 5.5 0a2.75 3.75 0 1 0-5.5 0Z");
}

</style>
