<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cp7pgylcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rating-stars-sharp" /></template>
<style>
.cp7pgylcr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.14 3.32l.96 2.15l.14.32l.35.04l2.34.24l.35.04l-.26.23l-1.75 1.58l-.26.23l.07.34l.49 2.31l.08.34l-.31-.17l-2.04-1.18l-.3-.18l-.3.18l-2.04 1.18l-.31.17l.08-.34l.49-2.31l.07-.34l-.26-.23l-1.75-1.58l-.26-.23l.35-.04l2.34-.24l.35-.04l.14-.32l.96-2.15L12 3zm-5 8l.89 1.99l.15.32l.34.04l2.17.23l.35.04l-.26.23l-1.62 1.46l-.26.24l.07.34l.46 2.14l.07.34l-.31-.18l-1.89-1.09l-.3-.17l-.3.17l-1.89 1.09l-.31.18l.07-.34l.46-2.14l.07-.34l-.26-.24l-1.62-1.46l-.26-.23l.35-.04l2.17-.23l.34-.04l.15-.32l.89-1.99L7 11zm10 0l.89 1.99l.15.32l.34.04l2.17.23l.35.04l-.26.23l-1.62 1.46l-.26.24l.07.34l.46 2.14l.07.34l-.31-.18l-1.89-1.09l-.3-.17l-.3.17l-1.89 1.09l-.31.18l.07-.34l.46-2.14l.07-.34l-.26-.24l-1.62-1.46l-.26-.23l.35-.04l2.17-.23l.34-.04l.15-.32l.89-1.99L17 11z");
}

</style>
