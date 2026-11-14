<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mervg3bjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:suspension-trainer" /></template>
<style>
.mervg3bjt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5V8m0 3l-5 6m5-6l5 6m-6.5-9h3v3h-3Zm-6 9h5v3.5h-5Zm10 0h5v3.5h-5Z");
}

</style>
