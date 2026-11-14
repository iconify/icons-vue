<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvs1k7bwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:water-network-map" /></template>
<style>
.dvs1k7bwe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.5s-2.75 3.25-2.75 5a2.75 2.75 0 0 0 5.5 0c0-1.75-2.75-5-2.75-5Zm2.75 5h6.25m-9 2.75v5.25m2-6.25l7.75 7M15.5 7.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM4 18a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm11.5 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

</style>
