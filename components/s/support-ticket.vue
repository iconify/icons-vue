<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="op2k1_kkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:support-ticket" /></template>
<style>
.op2k1_kkn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 5h10a1.5 1.5 0 0 0 3 0h2a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2h-2a1.5 1.5 0 0 0-3 0h-10a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2ZM16 9v6M6 10h5.5M6 14h4");
}

</style>
