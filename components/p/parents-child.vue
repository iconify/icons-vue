<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bnhdk3hvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:parents-child" /></template>
<style>
.bnhdk3hvy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 6.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m10 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0m-11.5 11c0-3 2-5 4.5-5h.074m9.901 0H17c2.5 0 4.5 2 4.5 5m-11.75-4a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m-2.25 8c0-2 2-3 4.5-3s4.5 1 4.5 3");
}

</style>
