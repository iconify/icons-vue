<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhsi2sb6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shoe-rack" /></template>
<style>
.xhsi2sb6c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 21.5v-19m17 19v-19M3.5 11h17m-17 9h17M7 11V6.5h2.5l2 2.25l4 .75q1 .25 1 1.5M7 20v-4.5h2.5l2 2.25l4 .75q1 .25 1 1.5");
}

</style>
