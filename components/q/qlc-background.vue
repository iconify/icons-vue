<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="hj2utbb4a"/><path class="snzvatbhz"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:qlc-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hj2utbb4a {
  fill: var(--svg-color--05c7ff, #05c7ff);
  d: path("M12 17.486a.67.67 0 0 0 0-1.34a4.14 4.14 0 0 1-4.15-4.15a.67.67 0 0 0-1.335 0A5.485 5.485 0 0 0 12 17.49zm0-10.97a.67.67 0 1 0 0 1.34a4.136 4.136 0 0 1 4.15 4.15a.67.67 0 0 0 1.335 0A5.487 5.487 0 0 0 12 6.516");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.snzvatbhz {
  fill: var(--svg-color--05c7ff, #05c7ff);
  d: path("M12.005 9A2.984 2.984 0 0 1 15 12a.69.69 0 0 1-1.375 0A1.625 1.625 0 1 0 12 13.63A.689.689 0 0 1 12 15a3 3 0 0 1-2.12-.88A3 3 0 0 1 12.004 9m2.775 5.78a.734.734 0 0 0 0-1.05l-.01-.015a.75.75 0 0 0-1.05 0a.75.75 0 0 0 0 1.055l.005.01a.74.74 0 0 0 1.055 0M12 4a.67.67 0 0 0 0 1.34A6.65 6.65 0 0 1 18.665 12A.67.67 0 0 0 20 12c0-2.21-.9-4.215-2.345-5.66A8 8 0 0 0 12 4m0 16a.67.67 0 0 0 0-1.34A6.65 6.65 0 0 1 5.335 12A.668.668 0 1 0 4 12.01c0 2.21.9 4.21 2.345 5.65A7.95 7.95 0 0 0 12 20");
}

</style>
