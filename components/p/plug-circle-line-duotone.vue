<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="r0fjgcb6p"/><path class="h0rtdjbeb"/><path class="ndcdy4d6d"/><path class="zvfketbhl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:plug-circle-line-duotone" /></template>
<style>
.h0rtdjbeb {
  stroke-linejoin: round;
  d: path("M9 11.8C9 11.3582 9.35817 11 9.8 11H14.2C14.6418 11 15 11.3582 15 11.8V12C15 13.6569 13.6569 15 12 15C10.3431 15 9 13.6569 9 12V11.8Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ndcdy4d6d {
  d: path("M13.5 11V9");
}

.r0fjgcb6p {
  d: path("M12 15.1082V20.1498C12 21.2635 11.0955 22.1875 10.0128 21.9673C5.44193 21.0381 2 16.9659 2 12.0832C2 6.51441 6.47715 2 12 2C17.5228 2 22 6.51441 22 12.0832C22 16.0744 19.7003 19.5239 16.3641 21.1581");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.zvfketbhl {
  d: path("M10.5 11V9");
}

</style>
