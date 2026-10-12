<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iblq6ibxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:zipper-sharp" /></template>
<style>
.iblq6ibxu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 2.75h3V6h-3zM8.75 6H16l-.13.74l-.49 2.77l-.13.74h-6.5l-.13-.74l-.49-2.77L8 6zm0 4.25v11m6.5-11v11M8.75 13H11m4.25 2.25H13M8.75 17.5H11m4.25 2.25H13");
}

</style>
