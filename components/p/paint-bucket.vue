<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nv35edbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paint-bucket" /></template>
<style>
.nv35edbhf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m11 6l6 6l-7 7a1.414 1.414 0 0 1-2 0l-4-4a1.414 1.414 0 0 1 0-2zM8 3l3 3m-6 6h12m4 7a2 2 0 1 1-4 0c0-1 1-2 2-3c1 1 2 2 2 3");
}

</style>
