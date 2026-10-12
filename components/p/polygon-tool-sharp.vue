<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ng3cfeify"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:polygon-tool-sharp" /></template>
<style>
.ng3cfeify {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.84 6.4l4.82-1.55m3.48 1.17l2.97 3.21m.95 3.62l-1.87 5.05m-2.64 1.42L7.2 17.68m-2-2.34l-.15-6.43M3.5 5.5h3v3h-3zM12 2.75h3v3h-3zm6.25 6.75h3v3h-3zM15 18.25h3v3h-3zm-11.25-2.5h3v3h-3z");
}

</style>
