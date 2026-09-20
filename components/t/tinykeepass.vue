<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="i5rwi4sts"/><path class="y4ttiyb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tinykeepass" /></template>
<style>
.i5rwi4sts {
  cx: 13.05px;
  cy: 24px;
  r: 8.55px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y4ttiyb-y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 32.55V24H21.59m16.3 4.93V24");
}

</style>
