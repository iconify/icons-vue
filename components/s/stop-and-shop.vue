<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="r975nsb7x"/><circle class="gmvelmxic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:stop-and-shop" /></template>
<style>
.gmvelmxic {
  cx: 24px;
  cy: 35.182px;
  r: 9.318px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.r975nsb7x {
  cx: 24px;
  cy: 12.818px;
  r: 9.318px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
