<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqle2_bej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:repotting-pot-size" /></template>
<style>
.pqle2_bej {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4H14v3H2.5Zm1 3L5 19.5h6.5L13 7m3 5h5.5v2.75H16Zm.5 2.75l.75 4.75h3l.75-4.75");
}

</style>
