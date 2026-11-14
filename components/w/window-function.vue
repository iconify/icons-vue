<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xh2-ar-xp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:window-function" /></template>
<style>
.xh2-ar-xp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 2.5h6v19h-6Zm0 3.75h6M7.5 10h6m-6 4h6m-6 3.75h6M6 6.25H4.5v11.5H6m9-11.5h1.5v11.5H15M19.75 6.5v11M18 15.75l1.75 1.75l1.75-1.75");
}

</style>
