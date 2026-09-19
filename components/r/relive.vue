<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wwryanbdu"/><path class="vhsi8sbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:relive" /></template>
<style>
.vhsi8sbkh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.432 30.507c5.622-1.527 9.757-6.667 9.757-12.773c0-7.309-5.925-13.234-13.234-13.234s-13.234 5.925-13.234 13.234");
}

.wwryanbdu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.284 43.5L23.048 19.94L8.811 43.5");
}

</style>
