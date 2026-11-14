<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2g1c-bvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pet-lotion" /></template>
<style>
.x2g1c-bvw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 9h9v12.5h-9ZM8 9V3.5h5m5.5 6.5s3 3.5 3 5.5a3 3 0 0 1-6 0c0-2 3-5.5 3-5.5Z");
}

</style>
