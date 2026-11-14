<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmrsb0bpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:steam-mop" /></template>
<style>
.hmrsb0bpv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 17.5h13V21H6Zm5 0l6.5-15m-12 12c-1-1.5 1-3.5 0-5.5m3 5.5c-1-1.5 1-3.5 0-5.5");
}

</style>
