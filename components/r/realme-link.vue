<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="bw-1m4hnh"/><path class="s7xqaugqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:realme-link" /></template>
<style>
.bw-1m4hnh {
  cx: 24px;
  cy: 24px;
  r: 12.443px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.s7xqaugqi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.749 21.82L16.297 4.5m-4.548 17.32L11.557 24m24.694 2.18L31.703 43.5");
}

</style>
