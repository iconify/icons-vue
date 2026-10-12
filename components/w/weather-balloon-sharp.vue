<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zsxhg0u0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:weather-balloon-sharp" /></template>
<style>
.zsxhg0u0b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 14.5C9 13 7 11 7 8a5 5 0 0 1 10 0c0 3-2 5-5 6.5Zm0 0v4m-1.75 0h3.5v2.75h-3.5z");
}

</style>
