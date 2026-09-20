<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="wvq_a5b3d"/><path class="ha884jb-b"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mlk-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ha884jb-b {
  fill: var(--svg-color--fff, #fff);
  d: path("m18.334 7.17l-5.198-2.878a2.33 2.33 0 0 0-2.261 0L5.671 7.17A2.33 2.33 0 0 0 4.47 9.201V14.8c0 .845.462 1.62 1.202 2.031l5.197 2.877a2.33 2.33 0 0 0 2.262 0l5.197-2.877a2.33 2.33 0 0 0 1.201-2.031V9.2a2.33 2.33 0 0 0-1.195-2.032m-8.217 7.689c0 .768-.64 1.376-1.411 1.376c-.772 0-1.412-.608-1.412-1.377v-4.765c0-.77.64-1.387 1.412-1.387s1.411.617 1.411 1.387zM12 12.47a1.416 1.416 0 0 1-1.412-1.411c0-.775.634-1.412 1.412-1.412s1.412.637 1.412 1.412S12.777 12.47 12 12.47m4.706 2.388c0 .77-.64 1.377-1.412 1.377s-1.412-.608-1.412-1.377v-4.765c0-.77.64-1.387 1.412-1.387s1.412.617 1.412 1.387z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.wvq_a5b3d {
  fill: var(--svg-color--5dbab8, #5dbab8);
  d: path("M24 0H0v24h24z");
}

</style>
