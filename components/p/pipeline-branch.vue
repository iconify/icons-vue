<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxwmu0xnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pipeline-branch" /></template>
<style>
.gxwmu0xnb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 20.5v-7l-6-6M7 4l5 5l5-5m3.5 3.5l-6 6v7m-12-12L8 3m8 0l5.5 5.5M8 20.5h8");
}

</style>
