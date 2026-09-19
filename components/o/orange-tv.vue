<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xw8nubc0w"/><circle class="v0xsv5b1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:orange-tv" /></template>
<style>
.v0xsv5b1r {
  cx: 24.036px;
  cy: 35.466px;
  r: 0.75px;
  fill: currentColor;
}

.xw8nubc0w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.484 10.428h39v22.886h-39zm6.876 22.886h25.353v4.304H11.36z");
}

</style>
