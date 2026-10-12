<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5yk-pbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:terrain-sharp" /></template>
<style>
.j5yk-pbfw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.25c2-4.5 4.75-7 8.25-7s6.5 2.5 10.25 3.5v3.5Zm0-7.75l5-7l3.5 4.75l2.5-3L17.5 12");
}

</style>
