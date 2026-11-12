<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="yodzen-to"/><circle class="p1e355btg"/><path class="bu7s7beka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:routing-3-broken" /></template>
<style>
.bu7s7beka {
  stroke-linejoin: round;
  d: path("M10.9997 5H16.1316C18.1325 5 18.8934 7.61309 17.2054 8.68732L13.6026 10.98M12.9997 19H7.86784C5.86695 19 5.10602 16.3869 6.7941 15.3127L9.99976 13.2727M11.4997 20.5L12.9997 19L11.4997 17.5");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p1e355btg {
  cx: 19px;
  cy: 19px;
  r: 3px;
}

.yodzen-to {
  cx: 5px;
  cy: 5px;
  r: 3px;
}

</style>
