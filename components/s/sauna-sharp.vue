<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dojlr6z_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sauna-sharp" /></template>
<style>
.dojlr6z_a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 9L6.15 7.5L7.5 6l1.35-1.5L7.5 3M11 9L9.65 7.5L11 6l1.35-1.5L11 3m4 8.25l4.25-6.75m-1.5-.25a1.75 1.75 0 1 0 3.5 0m-16.5 7H17.5l-.19 1.24l-1.12 7.52l-.19 1.24H5l-.19-1.24l-1.12-7.52l-.19-1.24zm-.6 4.25h12.7");
}

</style>
