<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="tbx_jt01d"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xhv-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.tbx_jt01d {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.5 9.15L7 13.76v4.74h2.5v-3.605l7.5-4.62V5.5h-2.5zM13 8.375V4h5.5v7.165l-7.5 4.51V20H5.5v-7.09zM5.5 4H11v4.375l-1.5.77V5.5H7v5.185l-1.5.77zM13 15.67l1.5-.785V18.5H17v-5.165l1.5-.775V20H13z");
}

</style>
