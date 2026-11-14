<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mffsyvrym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pills-two" /></template>
<style>
.mffsyvrym {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.25 9a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0m10.5 6a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0M2.25 9h9m1.5 6h9");
}

</style>
