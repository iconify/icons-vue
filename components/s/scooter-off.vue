<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpvxyqbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:scooter-off" /></template>
<style>
.lpvxyqbok {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 18.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm18.196-1.195q-.169-.309-.415-.56q-.247-.25-.554-.423M3 16h9.1m6.9-.9V4m-3 0h5.5m-18-.5l17 17");
}

</style>
