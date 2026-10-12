<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lz2820bcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sort-descending" /></template>
<style>
.lz2820bcw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 6.5h9m-9 5.5h6.5m-6.5 5.5h4m9.5-12.75v14.5m-3.5-3.5l3.5 3.5l3.5-3.5");
}

</style>
