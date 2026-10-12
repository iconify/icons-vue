<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwe96ac4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shampoo-bottle-sharp" /></template>
<style>
.pwe96ac4f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3.5h7.5m-2.5 0v2.75m-2.25 0h4.5v2.5h-4.5zm-3.5 5.5h11.5v9.5H6.25zM9.5 16.5h5");
}

</style>
