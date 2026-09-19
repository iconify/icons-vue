<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="f-5wm485e"/><path class="bm4i4_bjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nuclear" /></template>
<style>
.bm4i4_bjb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.45 24a6.45 6.45 0 0 0-3.225-5.586L34.75 5.38A21.5 21.5 0 0 1 45.5 24zm-9.675 5.586a6.45 6.45 0 0 0 6.45 0L34.75 42.62a21.5 21.5 0 0 1-21.5 0zm0-11.172A6.45 6.45 0 0 0 17.55 24H2.5A21.5 21.5 0 0 1 13.25 5.38z");
}

.f-5wm485e {
  cx: 24px;
  cy: 24px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
