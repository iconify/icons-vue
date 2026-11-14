<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cd2wt5bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pills-two" /></template>
<style>
.cd2wt5bjr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.25 9a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Zm10.5 6a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0ZM2.25 9h9m1.5 6h9");
}

</style>
