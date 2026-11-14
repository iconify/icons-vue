<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqnfgcbej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tax-bracket-steps" /></template>
<style>
.xqnfgcbej {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.6 19.5H2.5v-5h5.25V9H13V3.5h5.25v9.15m-3.5 8.6l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

</style>
