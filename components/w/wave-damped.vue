<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ol4xmv0ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wave-damped" /></template>
<style>
.ol4xmv0ro {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3v18m0-9C3.75 2.75 5.75 2.75 7 12c1 6.75 3 6.75 4 0c.75-4.75 2.75-4.75 3.5 0c.75 3.25 2.25 3.25 3 0h4");
}

</style>
