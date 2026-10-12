<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0aixhb0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:twig-sharp" /></template>
<style>
.u0aixhb0s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 20.25L17 7m-8 8l-.75-5.25m5.25.75l4.75.75M17 7c-.25-2 .75-3.5 2.75-4.25c.5 2-.75 3.75-2.75 4.25Z");
}

</style>
