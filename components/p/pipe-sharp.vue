<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wj5rb-xhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pipe-sharp" /></template>
<style>
.wj5rb-xhn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 5.25H15A4.75 4.75 0 0 1 19.75 10v8h-5v-7.75h-9Zm-3-1.5h3v8h-3zM13.5 18H21v3h-7.5z");
}

</style>
