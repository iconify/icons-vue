<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nq6ottbbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sports-bag" /></template>
<style>
.nq6ottbbu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 9h15a2 2 0 0 1 2 2v7.5a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2V11a2 2 0 0 1 2-2Zm2 0a5.5 5.5 0 0 1 11 0m-11 0v11.5M17.5 9v11.5");
}

</style>
