<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpx3oybuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:serving-tray-sharp" /></template>
<style>
.jpx3oybuh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 8.5h5v5.25h-5zm9-1.5h4.5l-.11.99l-.53 4.77l-.11.99h-4l-.11-.99l-.53-4.77l-.11-.99zm-11.5 9.25h18.5l-1.4 2.8l-.514 1.179l-1.286.021H5.95l-1.286-.021l-.514-1.179Z");
}

</style>
