<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdfjmtr7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spoon-sharp" /></template>
<style>
.rdfjmtr7s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.61 12.39a5.5 3.75-45 0 1 7.78-7.78a5.5 3.75-45 0 1-7.78 7.78Zm-.36.36L4 20");
}

</style>
