<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lw51dibbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:organic-cosmetics" /></template>
<style>
.lw51dibbx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 11h16v10.5H4Zm2-3h12v3H6Zm6 0c.5-3.25 2.75-5 6.5-5.25C18.25 6 16 8 12 8Z");
}

</style>
