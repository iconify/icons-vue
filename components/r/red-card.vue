<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxpor-bis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:red-card" /></template>
<style>
.vxpor-bis {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.621 4.263l3.668.78a2.625 2.625 0 0 1 2.022 3.113l-1.819 8.559a2.625 2.625 0 0 1-3.113 2.022l-3.668-.78a2.625 2.625 0 0 1-2.022-3.113l1.819-8.559a2.625 2.625 0 0 1 3.113-2.022M19.75 9.75L21.5 7.5m-18.75-1l2 1.75");
}

</style>
