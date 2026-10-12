<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="su2gymbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:office-plant-sharp" /></template>
<style>
.su2gymbsc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 14.25V3.5M9.25 14.25C9 11 8 8.75 6.25 7m8.5 7.25C15 11 16 8.75 17.75 7m-11.5 7.25h11.5l-1 6l-.208 1.021l-1.042-.021h-7l-1.042.021l-.208-1.021Z");
}

</style>
