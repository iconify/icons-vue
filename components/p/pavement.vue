<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_p_6sbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pavement" /></template>
<style>
.u_p_6sbbi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 4.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm1.5 5L11.5 15m-3-2.5l4.25-2.5L16 12.75M8 21.5l3.5-6.5l4 6.5m-13 0h19");
}

</style>
