<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zofo2hb3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:price-book-add" /></template>
<style>
.zofo2hb3a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M21.5 15.153V4C17 3.5 14 4 12 5.5C10 4 7 3.5 2.5 4v13.5C7 17 10 17.5 12 19q.121-.091.247-.177M12 5.5V19m6-4v6m-3-3h6");
}

</style>
