<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="le1de84yy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tooth-sensitive" /></template>
<style>
.le1de84yy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.038 16.625c.542-2.254.817-4.189 1.462-6.125c.75-2.5 1-5.25-.75-6.5c-1.5-1-3.75-.5-5.25 1C8 3.5 5.75 3 4.25 4c-1.75 1.25-1.5 4-.75 6.5c.75 2.25 1 4.5 1.75 7.25c.5 1.75 2 1.75 2.5 0l.75-3.5c.25-1 1.75-1 2 0l.75 3.5c.175.612.472 1.01.806 1.194M19.5 14.5l-3 3.5H20l-2.75 3.5");
}

</style>
