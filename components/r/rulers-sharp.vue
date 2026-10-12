<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjhv6acdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rulers-sharp" /></template>
<style>
.pjhv6acdz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.78 9.52L9.52 19.78l-1.41 1.41l-1.41-1.41l-2.48-2.48l-1.41-1.41l1.41-1.41L14.48 4.22l1.41-1.41l1.41 1.41l2.48 2.48l1.41 1.41zm-6.54-4.06l2.47 2.47m-4.42-.53l1.59 1.59m-3.53.36l2.47 2.47m-4.42-.53l1.59 1.59m-3.53.36l2.47 2.47");
}

</style>
