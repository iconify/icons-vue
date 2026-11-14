<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_5epvm5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pe-kit" /></template>
<style>
.a_5epvm5a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4 6l4.5-2.5c1 1.5 2 2 3.5 2s2.5-.5 3.5-2L20 6l-2 4.5l-2-1V20H8V9.5l-2 1Z");
}

</style>
