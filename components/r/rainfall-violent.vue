<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="en8g9-zwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rainfall-violent" /></template>
<style>
.en8g9-zwv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 13.5h10a4 4 0 0 0 0-8a5.5 5.5 0 0 0-10 1a3.5 3.5 0 0 0 0 7Zm1 3L6.5 21m5.5-4.5L10.5 21m5.5-4.5L14.5 21m5.5-4.5L18.5 21");
}

</style>
