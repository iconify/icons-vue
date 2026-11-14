<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0nng_jsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:self-tanner" /></template>
<style>
.p0nng_jsd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 11.25h9l-1.25 7.25h-6.5Zm2 7.25h5v3h-5Zm0-10a2.5 2.5 0 0 1 5 0M12 3.25V2m4.5 3.75L17.75 5M7.5 5.75L6.25 5");
}

</style>
