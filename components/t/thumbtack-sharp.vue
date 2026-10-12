<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="di26q_r7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:thumbtack-sharp" /></template>
<style>
.di26q_r7p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 13.75h13v7.5h-13zm3 3.75h7M9.8 5.5a6 2.75 30 1 0 10.4 6a6 2.75 30 1 0-10.4-6Zm3.8 5.4l-1 1.7");
}

</style>
