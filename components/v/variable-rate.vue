<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7mtwv1ew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:variable-rate" /></template>
<style>
.s7mtwv1ew {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 11.25c.11.09-1.71 2.05-1.75 3.25a1.75 1.75 0 0 0 3.75 0c-.07-1.2-1.89-3.16-2-3.25Zm6.25-1.5C10.56 9.64 8.09 12.3 8 14a2.5 2.5 0 0 0 5 0c.03-1.7-2.44-4.36-2.5-4.25Zm7.75-2.25S15 11 15 13.25a3.25 3.25 0 0 0 6.5 0c0-2.25-3.25-5.75-3.25-5.75ZM2.5 20h19");
}

</style>
