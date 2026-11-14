<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5r95162k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rubber-gloves" /></template>
<style>
.u5r95162k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8 21.5l1.5-6l-3.75-3.75a1.5 1.5 0 0 1 2-2.25l.75.75V5a1.5 1.5 0 0 1 3 0v4v-5.25a1.5 1.5 0 0 1 3 0V9V5a1.5 1.5 0 0 1 3 0v8l-1 2.5l1.5 6Zm1-4h8");
}

</style>
