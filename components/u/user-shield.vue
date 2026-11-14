<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cw384kbgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:user-shield" /></template>
<style>
.cw384kbgl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20c0-2.75 2.9-4.75 6.5-4.75s6.5 2 6.5 4.75c0 .6-.4 1-1 1h-11c-.6 0-1-.4-1-1ZM5.25 8.25a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0ZM18.5 6.5l3 1.25v2.75c0 2.25-1.3 3.5-3 4.25c-1.7-.75-3-2-3-4.25V7.75Z");
}

</style>
