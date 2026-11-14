<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gsl2x60ra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:planter-barrier" /></template>
<style>
.gsl2x60ra {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11.5h19v7h-19Zm3.5 7V21m12-2.5V21m-6-9.5v-6M12 9C9.5 9 7.5 7.5 7.5 5C10 5 12 6.5 12 9Zm0-1.5C12 5 14 3 16.5 3c0 2.5-2 4.5-4.5 4.5Z");
}

</style>
