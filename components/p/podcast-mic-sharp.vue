<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykp-3ebtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:podcast-mic-sharp" /></template>
<style>
.ykp-3ebtx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.75h9V13.5h-9zm0 5h9m-9 2.75h9m-4.5 3V16m4.5-7.5h3.5v12.75m-4.5 0h8.5");
}

</style>
