<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-kc_eboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ocean-plastic-sharp" /></template>
<style>
.l-kc_eboh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 3h2.5v2l2 .857v7.393h-6.5V5.857l2-.857Zm-8 13.5c1.5 0 1.5-1 3.08-1c1.5 0 1.5 1 3.08 1c1.5 0 1.5-1 3.08-1c1.5 0 1.5 1 3.08 1c1.5 0 1.5-1 3.08-1c1.5 0 1.5 1 3.08 1m-18.48 4c1.5 0 1.5-1 3.08-1c1.5 0 1.5 1 3.08 1c1.5 0 1.5-1 3.08-1c1.5 0 1.5 1 3.08 1c1.5 0 1.5-1 3.08-1c1.5 0 1.5 1 3.08 1");
}

</style>
