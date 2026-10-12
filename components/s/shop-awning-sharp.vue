<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ph5q3pbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shop-awning-sharp" /></template>
<style>
.ph5q3pbyx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.8 3.75h10.4l.791-.002l.449.652l2.6 3.8l.22.37l-.01.43a2.31 2.31 0 0 1-4.63 0A2.31 2.31 0 0 1 12 9a2.31 2.31 0 0 1-4.63 0a2.31 2.31 0 0 1-4.62 0v-.5l.013-.438l.247-.362l2.55-3.3l.449-.652zm2.95 0L7.37 9M12 3.75V9m2.25-5.25L16.62 9m-6.93 2.3v3.2m4.62-3.2v3.2m-7.56 0h10.5v6.75H6.75zm3 3.25h4.5");
}

</style>
