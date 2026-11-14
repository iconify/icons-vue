<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyz9cr0ru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:nuclear-fission" /></template>
<style>
.dyz9cr0ru {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 6a6 6 0 0 0 0 12Zm6 0a6 6 0 0 1 0 12Zm-3 1h.01M12 10.5v3m0 3.5h.01");
}

</style>
