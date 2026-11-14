<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jf1u90b-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:now-next-later" /></template>
<style>
.jf1u90b-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h4.75v6H2.5ZM9.75 5h4.75v6H9.75Zm7 2.5h4.75v6h-4.75ZM3 19h18m-2.5-2.5L21 19l-2.5 2.5");
}

</style>
