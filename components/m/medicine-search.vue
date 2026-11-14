<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gr40ddc-q"/><path class="jv2pl9bin"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:medicine-search" /></template>
<style>
.gr40ddc-q {
  d: path("M2.5 10a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0Zm13 5.5L21 21");
}

.jv2pl9bin {
  d: path("m11.414 5.757l2.829 2.829l-5.657 5.657l-2.829-2.829ZM8.586 8.586l2.828 2.828");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
