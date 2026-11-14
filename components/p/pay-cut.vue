<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ool9pdb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pay-cut" /></template>
<style>
.ool9pdb4t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8.5H7v13H2.5Zm7.25 4h4.5v9h-4.5Zm7.25 4h4.5v5H17Zm-14.5-5H7m-4.5 3.25H7M2.5 18H7m2.75-2.5h4.5m-4.5 3h4.5M17 19h4.5M10 3l10.5 9.5m0-3.5v3.5H17");
}

</style>
