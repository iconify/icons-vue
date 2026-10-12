<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpwvu7x9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:patio-sharp" /></template>
<style>
.rpwvu7x9w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 9.5C4.5 5.5 8 3.25 12 3.25s7.5 2.25 8.75 6.25Zm8.75 0v5.75m-4.75 0h9.5m-8.25 0l-1 6m8-6l1 6");
}

</style>
