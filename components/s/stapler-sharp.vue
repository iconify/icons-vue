<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kadjsqbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stapler-sharp" /></template>
<style>
.kadjsqbrq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 13v-2.317L6 10.25l11.75-2.3l3.001-.613l-.001 3.063v.4l-.008 1.625l-1.592.325l-13 2.6l-2.388.488L3.75 13.4Zm-1 4.75h18.5v3.5H2.75zM5 15.25v2.5");
}

</style>
