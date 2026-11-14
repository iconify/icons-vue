<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tawwqqbpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:trowel-plaster" /></template>
<style>
.tawwqqbpg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.752 4.931l-4.453 2.024a1.75 1.75 0 0 0-.513 2.831l2.428 2.428a1.75 1.75 0 0 0 2.831-.513l2.024-4.453a1.75 1.75 0 0 0-2.317-2.317M13 11l-3 3m-6.005 3.884l3.889-3.889a1.5 1.5 0 0 1 2.121 0a1.5 1.5 0 0 1 0 2.121l-3.889 3.889a1.5 1.5 0 0 1-2.121 0a1.5 1.5 0 0 1 0-2.121");
}

</style>
