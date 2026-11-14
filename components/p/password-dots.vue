<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8fklebny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:password-dots" /></template>
<style>
.c8fklebny {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 8v5m-2-3.75l4 2.5m-4 0l4-2.5M12 8v5m-2-3.75l4 2.5m-4 0l4-2.5M19.5 8v5m-2-3.75l4 2.5m-4 0l4-2.5M2.5 17h19");
}

</style>
