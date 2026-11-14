<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsdchfb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:snow-blower" /></template>
<style>
.xsdchfb5o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.625 11.5h5.25a2.625 2.625 0 0 1 2.625 2.625v3.75a2.625 2.625 0 0 1-2.625 2.625h-5.25A2.625 2.625 0 0 1 11 17.875v-3.75a2.625 2.625 0 0 1 2.625-2.625M3.25 19a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M11 13.5L4.5 5h-2M15 11.5L16.5 7H19m-2-3.5h.01M20 3h.01m1.74 2.75h.01");
}

</style>
