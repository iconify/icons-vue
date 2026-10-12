<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryo_gobol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:split-bill-sharp" /></template>
<style>
.ryo_gobol {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 2.75h-6.5v18.5l2.25-1.5l2.15 1.5l2.1-1.5ZM7 7.75h1.5M7 11.25h1.5m4.75-8.5h6.5v18.5l-2.25-1.5l-2.15 1.5l-2.1-1.5Zm2.25 5H17m-1.5 3.5H17");
}

</style>
