<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru0vgprec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mesh-node" /></template>
<style>
.ru0vgprec {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 5a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM2 18.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm14 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM10.5 7.75l-4 8m7-8l4 8M8 18.5h8");
}

</style>
