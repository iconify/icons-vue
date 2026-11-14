<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdjh8zc6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shinai" /></template>
<style>
.pdjh8zc6e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.464 19.414l4.95-4.95l2.122 2.122l-4.95 4.95ZM6.5 13.5l4 4m-2-2l9-9m3.25-1.25L17.5 6.5l1.25-3.25");
}

</style>
