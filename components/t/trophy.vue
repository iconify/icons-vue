<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9soq5s3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:trophy" /></template>
<style>
.k9soq5s3z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3.5h10v6a5 5 0 0 1-10 0Zm0 2H5a2 2 0 0 0 0 4h2m10-4h2a2 2 0 0 1 0 4h-2m-5 5V20m-4 0h8");
}

</style>
