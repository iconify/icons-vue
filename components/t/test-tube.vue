<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8-g3l3ln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:test-tube" /></template>
<style>
.x8-g3l3ln {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14.051 3.947l3.898 2.25l-8 13.856l-3.898-2.25Zm-1.299-.75l6.496 3.75m-9.947 5.227l3.898 2.25");
}

</style>
