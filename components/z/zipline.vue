<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfynmvubt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:zipline" /></template>
<style>
.mfynmvubt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.75 6l18.5 4M12 8v1.5m-1.25 4.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m1.25 0h.01m-.01 2V18l-3 3m3-3l3 3");
}

</style>
