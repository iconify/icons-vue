<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-zizq5tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:text-layer-sharp" /></template>
<style>
.h-zizq5tc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.75h15.5v4.5h-6v10h-4.5v-10h-6v-4.5zm2 2.25h10.5M12 5v10m-5.25 5.75h10.5");
}

</style>
