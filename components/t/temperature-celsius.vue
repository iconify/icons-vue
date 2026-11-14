<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9uolhb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:temperature-celsius" /></template>
<style>
.o9uolhb-s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 14.5V5a2.5 2.5 0 0 1 5 0v9.5a4 4 0 1 1-5 0Zm8-7a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0ZM8 11v6.5");
}

</style>
