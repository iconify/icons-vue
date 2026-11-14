<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogyenk_zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:swing-analyzer" /></template>
<style>
.ogyenk_zc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.5 2.5L9 17.5m0 0L8 21H4a1.5 1.5 0 0 1-1.5-1.5v-1m.5-5A12 12 0 0 1 8 4m8.5 16h.01m-.01-3a3 3 0 0 1 3 3m-3-5.25A5.25 5.25 0 0 1 21.75 20");
}

</style>
