<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrdopcb0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shrink-sharp" /></template>
<style>
.rrdopcb0g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 12h15.5M12 3.75V9M8.75 5.75L12 9l3.25-3.25M12 20.25V15m-3.25 3.25L12 15l3.25 3.25");
}

</style>
