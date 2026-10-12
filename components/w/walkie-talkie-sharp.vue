<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4em8lqld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:walkie-talkie-sharp" /></template>
<style>
.g4em8lqld {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 7.25h10.5v13.5H6.75zm2.75 0v-4.5m5 4.5v-1.5M9.75 11h4.5m-4.5 2.5h4.5M9.75 16h4.5");
}

</style>
