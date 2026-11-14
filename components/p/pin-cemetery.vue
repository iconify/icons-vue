<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixwcd-wxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-cemetery" /></template>
<style>
.ixwcd-wxg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 21V11H4.5V7H9V2.5h4V7h4.5v4H13v10Zm-5 0h5m10 1l-2.25-2.75a2.75 2.75 0 1 1 4.5 0Z");
}

</style>
