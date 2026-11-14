<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sk6zo0hzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:seed-sunflower" /></template>
<style>
.sk6zo0hzy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5c3.5 3.5 5.5 9 5 13c-.5 3.5-2.5 6-5 6s-4.5-2.5-5-6c-.5-4 1.5-9.5 5-13ZM10.5 11v7m3-7v7");
}

</style>
