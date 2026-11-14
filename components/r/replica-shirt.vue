<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0k0d_6sp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:replica-shirt" /></template>
<style>
.i0k0d_6sp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9 3l3 3.5L15 3l5.5 2.5l1 5l-3.5 1V21H6v-9.5l-3.5-1l1-5Zm0 0h6");
}

</style>
