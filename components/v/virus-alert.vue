<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hnepr8b9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:virus-alert" /></template>
<style>
.hnepr8b9s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 10.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Zm3.25-6V7m0 7v2.5m-6-6H6m7 0h2.5M7 8L5.25 6.25M12 8l1.75-1.75M7 13l-1.75 1.75M12 13l1.75 1.75M18 15v3.25M18 21h.01");
}

</style>
