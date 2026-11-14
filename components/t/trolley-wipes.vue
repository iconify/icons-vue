<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="df0iljbho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:trolley-wipes" /></template>
<style>
.df0iljbho {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5H5l2.25 10H17l2-7H5.75m-1 11.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm5.75 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm8.5-2.25q.5 2.25 2.75 2.75q-2.25.5-2.75 2.75q-.5-2.25-2.75-2.75Q18.5 18 19 15.75Z");
}

</style>
