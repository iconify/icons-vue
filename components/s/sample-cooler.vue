<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="moxh847tn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sample-cooler" /></template>
<style>
.moxh847tn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8h18v13.5H3Zm0 3.5h18M8 8V5c0-1.1.9-2 2-2h4c1.1 0 2 .9 2 2v3m-4 6v5m2.165-3.75l-4.33 2.5m0-2.5l4.33 2.5");
}

</style>
