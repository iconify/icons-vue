<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tj-rq9b-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:man-sharp" /></template>
<style>
.tj-rq9b-f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 9a3.5 3.5 0 0 0 7 0V4.5h-3.25l-.75.75l-.25-.25H8.5v3Zm-2 11.25h11.75v-.75c0-2-2.8-3.75-6.25-3.75S5.75 17.5 5.75 19.5v.75z");
}

</style>
