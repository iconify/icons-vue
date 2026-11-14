<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vegho8dmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tesla-coil" /></template>
<style>
.vegho8dmc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 9a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM9 14.5h6M7.5 18h9M6 21.5h12M7.75 6l-2-1l1-1.25L4 2.5M16.25 6l2-1l-1-1.25L20 2.5");
}

</style>
