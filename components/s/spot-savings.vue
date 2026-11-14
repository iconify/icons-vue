<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vz1m8y6ql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:spot-savings" /></template>
<style>
.vz1m8y6ql {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7 12.5l10-10m-11.5 2a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm9 6a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-2.5 5v6m-3-3l3 3l3-3");
}

</style>
