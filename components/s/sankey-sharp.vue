<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tieejrbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sankey-sharp" /></template>
<style>
.tieejrbqa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.75h3.5v12.5h-3.5zm15-3h3.5v6.5h-3.5zm0 12h3.5v6.5h-3.5zM6.25 9c6 0 5.5-3 11.5-3m-11.5 9c6 0 5.5 3 11.5 3");
}

</style>
