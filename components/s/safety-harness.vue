<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dn9a3vobi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:safety-harness" /></template>
<style>
.dn9a3vobi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 21.25V10A3.5 3.5 0 0 1 9 6.5h1.5a1.5 1.5 0 0 0 3 0H15a3.5 3.5 0 0 1 3.5 3.5v11.25Zm3-12l7 9.5m0-9.5l-7 9.5");
}

</style>
