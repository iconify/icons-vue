<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6o_3rbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:splint-sharp" /></template>
<style>
.y6o_3rbgt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 21.25V6A3.25 3.25 0 0 1 13 6v15.25ZM13 8.5h4.5v12.75H13zm-6.5 3.75h11m-11 5h11");
}

</style>
