<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygyfav30u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:open-shelving-kitchen" /></template>
<style>
.ygyfav30u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11h18M3 20h18M3.5 7.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m12.375-3h.25a2.625 2.625 0 0 1 2.625 2.625v1.25A2.625 2.625 0 0 1 16.125 11h-.25a2.625 2.625 0 0 1-2.625-2.625v-1.25A2.625 2.625 0 0 1 15.875 4.5M7 17h10l-1 3H8Z");
}

</style>
