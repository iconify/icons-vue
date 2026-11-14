<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhdb8rb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:plant-check" /></template>
<style>
.mhdb8rb5p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.722 18.945L11.5 20.5h-7l-1-7h9l-.467 3.267M8 13.5v-5c-.25-3-2.25-5-5.25-5c0 3 2.25 5 5.25 5C8.25 5.25 10.25 3 13.25 3c0 3-2 5.5-5.25 5.5m6.75 9.5l2 2L21 15.75");
}

</style>
