<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnbd3_fmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shift-overtime" /></template>
<style>
.mnbd3_fmg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.2 21.5H4v-19h13v9.2M4 7h13M7 10.5h.01m2.49 0H14M7 14h.01m2.49 0h3M7 17.5h.01m10.99-3v7M14.5 18h7");
}

</style>
