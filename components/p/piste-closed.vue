<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwc815v1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:piste-closed" /></template>
<style>
.cwc815v1q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.214 5.286L12 2.5l9.5 9.5l-2.804 2.804m-3.959 3.959L12 21.5L2.5 12l2.754-2.754M3.5 3.5l17 17");
}

</style>
