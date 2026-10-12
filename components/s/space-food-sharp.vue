<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgakl-buh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:space-food-sharp" /></template>
<style>
.tgakl-buh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 2.75h4V5.5h-4zm2 2.75V8M5.75 8h12.5v13.25H5.75zm0 3.25h12.5M9 15.5h6m-6 2.75h4");
}

</style>
