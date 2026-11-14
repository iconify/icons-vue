<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7cgzs7jy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stick-vacuum" /></template>
<style>
.u7cgzs7jy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 18.5h10v3h-10Zm5 0l3.25-5.25m1.564-6.698l3.816 2.384l-3.444 5.512l-3.816-2.384Zm2.603-4.364l3.816 2.384l-2.65 4.24l-3.816-2.384Z");
}

</style>
