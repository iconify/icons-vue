<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="edivtnb0e"/><path class="t2xgxy4hx"/><path class="yf1486bpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:volumee" /></template>
<style>
.edivtnb0e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m37.876 29.287l-4.627-2.644L37.875 24l4.625 2.643v5.286L24 42.5L5.5 31.929v-5.286L24 16.073l9.25 5.285l-4.625 2.643L24 21.358L5.5 31.929");
}

.t2xgxy4hx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 16.071L24 26.642l-4.624-2.643l-4.626 2.643L24 31.928l18.5-10.571zL24 5.5L5.5 16.071v5.286L10.125 24l4.626-2.643l-4.627-2.644");
}

.yf1486bpz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.876 18.715L24 10.785L5.5 21.358m37 5.285L24 37.214l-13.876-7.93M24 37.214V42.5m0-15.858v5.286m0-15.855v5.285M24 5.5v5.286");
}

</style>
